---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Reversing / Verkehren
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
      <blockquote><p>Reversing is this: bind your opponent's sword against their left and as soon as it conncets, push your pommel through under your right arm; at the same time withdraw your head well from their stroke to your right. Then press their blade or arm down from you with crossed hands so that you trap them such that they can no longer attack, but you make yourself space to work at will.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>