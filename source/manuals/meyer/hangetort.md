---
category: '1. Guards - Secondary'
manual: 'Meyer'
layout: page
title: Hanging Point / Hangetort
order: 7
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
      <p><blockquote>The figure in the image teaches you how to execute the Hanging Point, except that it does not show the arms extended enough. Therefore position yourself in this guard thus: stand with your right foot forward, and hold your weapon with arms extended in front of you such that the blade hangs somewhat down toward the ground. This posture is quite similar to the Ox, except that in the Ox you hold the arms vertically, but here they shall be extended forward in front of your face, and you let the sword hang toward the ground, which is why it is called the Hanging Point.</blockquote></p>

      <img class="card-image" src="/manuals/meyer/images/guards/hangetort-illustration.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>