---
category: 'Strikes - Secondary'
manual: 'Meyer'
title: Winding Cut / Windthau
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
      <blockquote><p>The Winding Cut is done in the following manner: if your opponent cuts at you from above, then cut from below with crossed hands from your left onto his sword, so that your pommel sticks out under your right arm. And as soon as it clashes, step with your left foot out from him well toward your left side, withdraw your pommel again in a loop back out toward your left side, so that in the impetus, your long edge connects with his head over his right arm behind his blade, or hits over his right arm (concerning which see the large figure on the right in Image H), and so that your sword flies out by your side; and quickly cut back opposite to it with the Cross; thus it is done.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>