---
category: '1. Guards - Secondary'
manual: 'Meyer'
layout: page
title: Unicorn / Einhorn
order: 9
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
      <p>The Unicorn is on both sides and is similar to the <a href="ochs">Ox</a> except with the point extended and upwards. It is the natural ending position of an <a href="unterhau">Unterhau</a>.</p>

      <img class="card-image" src="/manuals/meyer/images/guards/einhorn-illustration.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>