---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Running Off / Ablauffen
order: 5
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
      <blockquote><p>This is, from whichever side you bind your opponent's sword, then reverse your hands as soon as it touches and let it run off with the short edge down, and meanwhile pull your hilt up in the air for a stroke; and do this on both sides.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>