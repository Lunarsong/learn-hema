---
category: 'Guards - Core'
manual: 'Meyer'
layout: page
title: Day / Vom Tag
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
      <blockquote><p>Vom Tag is also called the High Guard <i>[Oberhut]</i> and is executed in the following manner: Stand with your left foot forward and hold your sword up over your head so that the point extends right upwards.</p></blockquote>

      <img class="card-image" src="/manuals/meyer/images/guards/vom-tag-illustration.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>