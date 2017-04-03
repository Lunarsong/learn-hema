---
category: 'Strikes - Secondary'
manual: 'Meyer'
title: Rebound Cut / Prellhau
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
      <blockquote><p>This is of two kinds; one is called the single, and the other the double.</p>

<p>The single is done thus: if your opponent cuts at you from above, then intercept his stroke with a Thwart. As soon as it clashes, pull the sword around your head and strike from your left with the outside flat at his ear, as shown by the large figure on the right in Image K, so that the sword rebounds back away. Pull it back around your head in the impetus of the rebound; cut with the Thwart to his left; thus it is done.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>