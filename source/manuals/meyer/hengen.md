---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Hanging / Hengen
order: 23
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
      <blockquote><p>Hanging is easy to understand from the <a href="verschieben">Sliding</a>. Do it thus:</p>

      <blockquote><p>When you stand in the Plow and your opponent cuts at you, then go up with your hilt so that the blade hands somewhat toward the ground and  catch their stroke on the flat of your blade. Then work with winding to the nearest opening.</p></blockquote>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>