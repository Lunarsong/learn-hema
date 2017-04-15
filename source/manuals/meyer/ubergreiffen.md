---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Gripping Over / Ubergreiffen
order: 27
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
      <blockquote><p>Gripping Over is thus: Strike from your right to their upper left opening, however in the strike grip with the fingers out over the quillons or shield while holding the thumb on the haft, then with the left hand raise the pommel and slash in on their head with hanging blade over or behind their parry.</p>

      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>