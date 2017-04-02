---
category: 'Guards - Secondary'
manual: 'Meyer'
layout: page
title: Long Point / Langort
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
      <p><blockquote>Stand with your Left foot forward, hold your Weapon with outstretched arms out in front of your face, so that you stand and point forward at your opponent’s face, and thus you stand in the Guard of the Long Point</blockquote></p>
      <img class="card-image" src="/manuals/meyer/images/guards/langort-illustration.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>