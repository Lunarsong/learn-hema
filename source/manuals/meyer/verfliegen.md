---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Flitting / Verfliegen
order: 7
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
      <blockquote><p>This happens thus: in the Onset or the middle of the work, when you cut at your opponent's opening and they go against you to catch your stroke in the air, then do not let their blade connect with your sword, but pull the stroke back in the air with a single motion to another opening. This work is very useful against an opponent who is only eager to chase your sword and not to harm your body.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>