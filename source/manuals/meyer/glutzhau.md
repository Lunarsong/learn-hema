---
category: '2. Strikes - Secondary'
manual: 'Meyer'
title: Clashing Cut / Glützhau
---

<link rel="import" href="/bower_components/polymer/polymer.html">
<link rel="import" href="shared-styles.html">

<dom-module id="{{ page.url | split:'/' | last | remove: '.html' }}-element">
  <template>
    <style include="shared-styles">
      :host {
        display: block;

        padding: 10px;
      }
    </style>

    <div class="card">
      <h1>{{ page.title }}</h1>
      <blockquote><p>The Clashing Cut is done thus: if someone cuts at you from above, then strike with the back of your hand against his stroke to the upper left opening; let your blade slip off on his blade with the outside flat so that in the impetus, the short edge hits his head, palm away from him.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>