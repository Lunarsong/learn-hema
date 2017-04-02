---
category: 'Guards - Core'
manual: 'Meyer'
title: Plow / Pflug
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
      <blockquote><p>The low parts are guarded with the Plough, whose two modes are similar figures for two sides, the Right and the Left, and so are named the Right and Left Plough, and both will become for you nothing else than stabs outward from below.</p>

      <p>The Right Plough is described as follows, stand with your right foot forward, hold your weapon with the hilt near your forward knee and your point pointing in your opponent’s face, as if you intend to stab him from below. While you are in the Right Plough, step forward with the Left foot and stand similarly to be in the Left Plough.</p></blockquote>

      <img class="card-image" src="/manuals/meyer/images/guards/pflug-illustration.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>