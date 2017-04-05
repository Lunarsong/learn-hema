---
category: '1. Guards - Core'
manual: 'Meyer'
layout: page
title: Ox / Ochs
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
      <blockquote><p>The high parts are guarded with the Ox, which is two moded, Right and Left, thus one can stand in the Ox in two modes, namely the Right and Left modes.</p>

      <p>The right Ox is performed thus: stand with your Left Foot forward, holding the Sword with the hilt next to your head, high and on the right side, so that your forward point is directed against your opponent’s face. For the Left Ox reverse this, namely stand with your Right Foot forward, hold your hilt near your head on its Left Side as said above.</p></blockquote>

      <img class="card-image" src="/manuals/meyer/images/guards/ochs-illustration.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>