---
category: '1. Guards - Secondary'
manual: 'Meyer'
layout: page
title: Crossed Guard / Schrankhut
order: 6
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
      <p><blockquote>The Crossed Guard is when you hold your sword with crossed hands in front of you with the point toward the ground.</blockquote></p>
      <img class="card-image" style="width:600px;" src="/manuals/meyer/images/guards/schrankhut-illustration.jpg">
      <p>The crossed guard is possibly the same as the Barrier Guard of the Liechtenauer tradition. For reference, the Barrier Guard from Pseudo-Peter_von_Danzig:</p>
      <p><blockquote>Thus position yourself with the Barrier-Guard on your left side: when you come to him with the pre-fencing, then stand with your right foot before and hold your sword near your left side on the earth with crossed hands (so that the short edge is above), and give an opening with the right side. If he then hews to the opening, then spring from the hew against him with your left foot well on his right side, and strike him with the short edge over the hands in the spring.</blockquote></p>
      <img class="card-image" style="width:600px;" src="/manuals/meyer/images/guards/ppvd-barrier-illustration.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>