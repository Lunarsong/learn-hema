---
category: '1. Guards - Secondary'
manual: 'Meyer'
layout: page
title: Wrath Guard / Zornhut
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
      <p><blockquote>The Wrath Guard is so named because this posture displays a wrathful attitude. It is done thus: stand with your left foot forward, and hold your sword on your right shoulder, such that the blade hangs down behind prepared for a stroke. And it is to be noted here that all the techniques that are executed from the guard of the Ox can also be carried out from the Wrath posture, except that one uses different conduct to deceive the opponent in this quarter; and sometimes you can use this guard, sometimes the other.</blockquote></p>
      <img class="card-image" src="/manuals/meyer/images/guards/zornhut-illustration.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>