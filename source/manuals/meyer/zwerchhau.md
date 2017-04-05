---
category: '2. Strikes - Master'
manual: 'Meyer'
title: Thwart / Zwerchhau
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
      <blockquote><p>For the Thwart, conduct yourself thus: in the Onset, position yourself in the Wrath Guard on the right, that is, set your left foot forward and hold your sword on your right shoulder as if you intended to deliver a Wrath Cut. If your opponent cuts at you from the Day or High, then cut at the same time as him with the short edge across from below against his cut; hold your quillons up over your head as a parrying for your head, and at the same time as the cut, step well to his left side. Thus you parry and hit simultaneously.</p></blockquote>

      <img style="width:600px;" class="card-image" src="/manuals/meyer/images/strikes/zwerchhau-illustration.jpg">

      <img style="width:400px;" class="card-image" src="/manuals/meyer/images/strikes/cutting_diagram_zwerchhau.png">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>