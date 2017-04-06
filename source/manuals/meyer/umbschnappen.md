---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Snapping Around / Umbschnappen
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
      <blockquote><p>Snapping around is of two kinds.</p>

      <blockquote><p>The one is when you come on their arm or blade by <a href="verkehren">reversing</a>, then hold their blade or arm firmly below you with the quillons and meanwhile let the blade snap around at their head.</p>

      <p>The other: if they have forced you down with reversing, then slip from them with your left foot towards their right, and with this, catch over their right arm with your pommel, jerk it down and let your weapon snap around out from under his blade with the short edge at their head, so that your hands come crosswise over one another.</p></blockquote>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>