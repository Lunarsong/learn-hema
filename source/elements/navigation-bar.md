---

---

<link rel="import" href="/bower_components/polymer/polymer.html">

<link rel="import" href="/bower_components/paper-styles/demo-pages.html">
<link rel="import" href="/bower_components/paper-menu/paper-menu.html">
<link rel="import" href="/bower_components/paper-menu/paper-submenu.html">
<link rel="import" href="/bower_components/paper-item/paper-item.html">
<link rel="import" href="/bower_components/paper-button/paper-button.html">
<link rel="import" href="/bower_components/iron-collapse/iron-collapse.html">
<link rel="import" href="/bower_components/iron-selector/iron-selector.html">

<dom-module id="navigation-bar">
  <template>
<style is="custom-style">
    .horizontal-section {
      padding: 0 !important;
    }

    .avatar {
      display: inline-block;
      width: 40px;
      height: 40px;
      border-radius: 50%;
      overflow: hidden;
      background: #ccc;
    }

    paper-item {
      --paper-item: {
        cursor: pointer;
      };
    }

    .sublist paper-item {
      padding-left: 30px;
    }

    .sublist2 paper-item {
      padding-left: 50px;
    }

    .paper-item-link {
    color: inherit;
    text-decoration: none;
  }
  </style>
    <iron-selector selected="[[page]]" attr-for-selected="name" class="drawer-list" role="navigation">
      <paper-menu attr-for-item-title="label" multi>
        {% assign groups = site.pages | where: "manual", "Meyer" | group_by: "category" | sort: "title" %}
        {% for group in groups %}
        <paper-submenu>
          <paper-item class="menu-trigger">{{ group.name }}</paper-item>
          <paper-menu class="menu-content sublist">
          {% for item in group.items %}
            <a class="paper-item-link" href="{{item.title | downcase }}" tabindex="-1">
              <paper-item>{{item.title}}</paper-item>
            </a>
          {%endfor%}
          </paper-menu>
        </paper-submenu>
        {% endfor %}
      </paper-menu>
    </iron-selector>

  </template>

  <script>

    Polymer({

      is: 'navigation-bar'

    });

  </script>

</dom-module>