---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Pressing Hands / Hendtrucken
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
      <blockquote><p>Pressing hands strongly resembles the slice on the arm since it is always executed as with the High and Low slice.</p>

      <blockquote><p>For example, if your opponent overruns you with cloddish blows, then go under their stroke with the Crown, or else a high parrying, or go under them with hanging and catch their sword on the flat of your blade. And when you come under their sword, then if they go back up from your weapon with their stroke, see that you pursue them with your forte and fall on them with your shield from below in front of his fists, so that you get them with the forte of your blade. Push them up away from you with your shield and cut long toward the opening.</p></blockquote>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>