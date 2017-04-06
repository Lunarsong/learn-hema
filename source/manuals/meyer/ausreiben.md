---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Wrenching / Außreissen
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
      <blockquote><p>If you bind from your right, reverse your sword in the bind, and pull out to your left side, so that you both stand close together in the bind. Thus endevour that you can come at your opponent with the pommel from below, between their arms, and wrench upward. Or if you have caught over their arms from above with your pommel, or to whatever way the winding wants to happen, then wrench downward.</p>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>