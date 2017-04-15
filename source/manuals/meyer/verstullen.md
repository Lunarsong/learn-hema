---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Forestalling / Verstüllen
order: 26
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
      <blockquote><p>Forestalling shall be driven thus: if one comes working unto you with all sorts of actions against the four openings, and strives then to move overhead, then fall with the slice on their arm or sword and don't let them come away again, but wherever they go, pursue them closely with the slice on their arm, and thus follow after them so that they cannot work, and as soon as you see your opportunity, push them away from you with the slice and let your weapon fly to the nearest opening.</p>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>