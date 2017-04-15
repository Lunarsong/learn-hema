---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Slicing / Schneiden
order: 4
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


      <p>Transcription:</p>
      <blockquote><p>This is also one of the true core techniques in the handwork; for when your opponent rushes upon you with quick and swift devices, you can stop and hinder them with no other technique better than with the slice, which you should hold in stock for yourself among all techniques as a particular gem to discover. Now you must execute the slice thus:</p>

      <blockquote><p>After you have caught your opponent's sword with the bind, you shall remain there to feel whether they intend to withdraw from the bind or strike around. As soon as they strike around, then pursue them with the long edge on their arm; push them back from you with your forte or shield, let your weapon fly and cut to the nearest opening before they can recover.</p></blockquote>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>