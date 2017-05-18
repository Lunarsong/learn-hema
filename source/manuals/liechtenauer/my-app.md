---

---

<!--
@license
Copyright (c) 2016 The Polymer Project Authors. All rights reserved.
This code may only be used under the BSD style license found at http://polymer.github.io/LICENSE.txt
The complete set of authors may be found at http://polymer.github.io/AUTHORS.txt
The complete set of contributors may be found at http://polymer.github.io/CONTRIBUTORS.txt
Code distributed by Google as part of the polymer project is also
subject to an additional IP rights grant found at http://polymer.github.io/PATENTS.txt
-->

<link rel="import" href="/bower_components/polymer/polymer.html">
<link rel="import" href="/bower_components/app-layout/app-drawer/app-drawer.html">
<link rel="import" href="/bower_components/app-layout/app-drawer-layout/app-drawer-layout.html">
<link rel="import" href="/bower_components/app-layout/app-header/app-header.html">
<link rel="import" href="/bower_components/app-layout/app-header-layout/app-header-layout.html">
<link rel="import" href="/bower_components/app-layout/app-scroll-effects/app-scroll-effects.html">
<link rel="import" href="/bower_components/app-layout/app-toolbar/app-toolbar.html">
<link rel="import" href="/bower_components/app-route/app-location.html">
<link rel="import" href="/bower_components/app-route/app-route.html">
<link rel="import" href="/bower_components/iron-pages/iron-pages.html">
<link rel="import" href="/bower_components/iron-selector/iron-selector.html">
<link rel="import" href="/bower_components/paper-icon-button/paper-icon-button.html">
<link rel="import" href="my-icons.html">
<link rel="import" href="navigation-bar.html">

<dom-module id="my-app">
  <template>
    <style>
      :host {
        --app-primary-color: #4285f4;
        --app-secondary-color: black;

        display: block;
      }

      app-header {
        color: #fff;
        background-color: var(--app-primary-color);
      }
      app-header paper-icon-button {
        --paper-icon-button-ink-color: white;
      }

      .drawer-list {
        margin: 0 20px;
      }

      .drawer-list a {
        display: block;
        padding: 0 16px;
        text-decoration: none;
        color: var(--app-secondary-color);
        line-height: 40px;
      }

      .drawer-list a.iron-selected {
        color: black;
        font-weight: bold;
      }
    </style>

    {% raw %}
    <app-location route="{{route}}"></app-location>
    <app-route
        route="{{route}}"
        pattern="/manuals/liechtenauer/:page"
        data="{{routeData}}"
        tail="{{subroute}}"></app-route>

    <app-drawer-layout fullbleed>
      <!-- Drawer content -->
      <app-drawer id="drawer">
        <div style="height: 100%; overflow: auto;">
          <app-toolbar>Menu</app-toolbar>
          <navigation-bar></navigation-bar>
        </div>
      </app-drawer>

      <!-- Main content -->
      <app-header-layout has-scrolling-region>

        <app-header condenses reveals effects="waterfall">
          <app-toolbar>
            <paper-icon-button icon="my-icons:menu" drawer-toggle></paper-icon-button>
            <div main-title>Liechtenauer Longsword</div>
          </app-toolbar>
        </app-header>
      {% endraw %}

        <iron-pages
            selected="[[page]]"
            attr-for-selected="name"
            fallback-selection="view404"
            role="main">
          <main-element name="main"></main-element>
          {% assign groups = site.pages | where: "manual", "Liechtenauer" | group_by: "category" | sort: "title" %}
          {% for group in groups %}
          {% for item in group.items %}
            <{{ item.url | split:'/' | last | remove: '.html' }}-element name="{{ item.url | split:'/' | last | remove: '.html' }}"></{{ item.url | split:'/' | last | remove: '.html' }}-element>

          {%endfor%}
          {% endfor %}
          <my-view404 name="view404"></my-view404>
        </iron-pages>
      </app-header-layout>
    </app-drawer-layout>
  </template>

  <script>
    Polymer({
      is: 'my-app',

      properties: {
        page: {
          type: String,
          reflectToAttribute: true,
          observer: '_pageChanged',
        },
      },

      observers: [
        '_routePageChanged(routeData.page)',
      ],

      _routePageChanged: function(page) {
        this.page = page || 'main';

        if (!this.$.drawer.persistent) {
          this.$.drawer.close();
        }
      },

      _pageChanged: function(page) {
        // Load page import on demand. Show 404 page if fails
        var resolvedPageUrl = this.resolveUrl(page + '.html');
        this.importHref(resolvedPageUrl, null, this._showPage404, true);
      },

      _showPage404: function() {
        this.page = 'view404';
      },
    });
  </script>
</dom-module>