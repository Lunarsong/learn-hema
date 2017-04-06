---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Slinging / Schlaudern
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
      <blockquote><p>This is simply when you let a cut fly with a fling against your opponent's head.</p>

      <blockquote><p>For example, position yourself in the guard of the Fool and pull your sword back through by your right side; just as you pull your sword back, step with your right foot toward your opponent and sling your cut at their head.</p></blockquote>

      <p>This Slinging Cut shall fly just as a stone is thrown from a sling. Whatever else is necessary concerning slinging you will find written later in the section on devices.</p>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>