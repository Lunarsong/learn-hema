---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Slicing Off / Abschneiden
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
      <blockquote><p>You should execute slicing off thus:</p>

      <blockquote><p>Hold the sword with your arms extended long in front of you, or sink into the guard of the Fool; if your opponent cuts at you with long cuts, then slice them off from you with the long edge to both sides until you see your opportunity to come to another work more suitable for you.</p></blockquote>

      <p>Chasing and the slice are also hidden within this slicing off. Therefore Liechtenauer also writes of this in a maxim where he says:</p>

      <blockquote><p>Slice off the hard ones<br>from both dangers.</p></blockquote>

      <p>That is, slice off the hard strokes from you from both sides.</p>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>