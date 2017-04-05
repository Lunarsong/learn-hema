---
category: '1. Guards - Secondary'
manual: 'Meyer'
layout: page
title: Side Guard / Nebenhut
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
      <blockquote><p>In this guard, position yourself thus: stand with your left foot forward, hold your sword by your right side, with the point toward the ground, so that the pommel stands upwards, and the short edge toward you.</p></blockquote>

      <p>This guard is not illustrated however it may be very similar to Fiore's Tail guard.</p>

      <img class="card-image" src="/manuals/meyer/images/guards/fiore-tail-illustration.png">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>