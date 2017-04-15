---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Setting Off / Absetzen
order: 8
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
      <blockquote><p>Since all combat devices require two things, namely cutting, and using the sword to bear off or parry the cuts, note that this handwork is the true bearing off or parrying, with which you do not simply catch the stroke without cutting back, but at the very moment the setting off connects, you hit to his opening with a step out.</p>

      <blockquote><p>For instance, if you come in the Onset into the Change and they cut at you from above, then go up with the long edge against their stroke and step the same time with your right foot toward their left and set them off; then at the moment it clashes, turn the short edge and flick it at their head.</p></blockquote>
      </blockquote>

      <p>It is useful to note in the example Meÿer gives us, one could also stab instead of flicking at the head. Meÿer avoids stabbing due to the etiquette of his time period.</p>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>