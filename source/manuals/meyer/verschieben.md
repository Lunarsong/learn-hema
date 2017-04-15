---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Sliding / Verschieben
order: 22
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


      <p>Transcription:</p>
      <blockquote><p>When you stand in the right Wrath and your opponent cuts at you, then let the blade hang behind you and slide your hanging blade over your head and under their blade, so that you catch their stroke on your flat, and your thumb lies under the flat of your shield. Then you can wind or else undertake a suitable work as seems best to you.</p>

      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>