---
category: 'Guards - Core'
manual: 'Meyer'
layout: page
title: Fool / Alber
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
      <blockquote><p>Stand with your left foot forward and hold your sword with the point extended toward the ground in front of you before your forward foot, such that the short edge lies above and the long edge below.</p></blockquote>

      <img class="card-image" src="/manuals/meyer/images/guards/alber-illustration.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>