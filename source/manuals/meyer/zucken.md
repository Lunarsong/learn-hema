---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Pulling / Zucken
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
      <blockquote><p>You can deceive your opponent masterfully with pulling, which is a very good handwork. You shall do it thus:</p>

      <blockquote><p>After you have bound your opponent or cut in at their opening with the long edge, then quickly pull back up as if you intended to cut at the other side; however, do not proceed, but quickly complete the cut with the short edge back at the spot from which you have gone away.</p></blockquote>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>