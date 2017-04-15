---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Barring / Sperren
order: 25
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
      <blockquote><p>Mark when one stands before you in the Change guard or Fool’s guard, then drop with long edge upon their blade, and just as it clashes or touches, cross over your hands and block them so that they can’t come out, or when they strikes up in front of you, drop with crossed hands onto the blade and block them.</p>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>