---
category: '1. Guards - Secondary'
manual: 'Meyer'
layout: page
title: Key / Schlüssel
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
      <blockquote><p>If you stand with your left foot forward and hold your sword with the hilt and crossed hands in front of your chest, so that the short edge lies on your left arm and the point is toward your opponent’s face, then this posture or guard is correctly executed.</p></blockquote>

      <img class="card-image" src="/manuals/meyer/images/guards/schlussel-illustration.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>