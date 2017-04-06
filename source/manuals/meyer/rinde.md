---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Looping / Rinde
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
      <blockquote>
      <p>There are two sorts of looping, single and double.</p>

      <p>Single looping is when you pull your sword away from your opponent's blade or opening in an arc over your head and let it fly around in the air so that you describe a circle.</p>

      <p>Double looping is when you pull away from their sword so strongly that it runs around twice in a continuous motion over your head, once to each side.</p>

      <p>These loopings, both single and double, are also very useful for deceiving.</p>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>