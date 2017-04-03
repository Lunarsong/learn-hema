---
category: 'Strikes - Secondary'
manual: 'Meyer'
title: Short Cut / Kurtzhau
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
      <blockquote><p>This is a stealthy action that goes through against your opponent, and is done thus: When your opponent cuts at you from above, then act as if you intended to bind on his sword with the Crooked Cut, that is with the short edge; but forego this, and quickly go through under his sword; strike with the short edge and crossed arms over his right arm at his head; thus you have caught his sword with the long edge and executed the Short Cut, and you stand at the end of it as shown by the figure on the right in the small scene on the upper left in Image B.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>