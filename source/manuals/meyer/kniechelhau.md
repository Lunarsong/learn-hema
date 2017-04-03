---
category: 'Strikes - Secondary'
manual: 'Meyer'
title: Wrist Cut / Kniechelhau
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
      <blockquote><p>This is so called from the body part to which it is directed. Do it thus: After the initial Onset, when you have come under your opponent’s sword with your hands up above your head, and he holds his head thus between his arms, then cut with Thwart Cuts under his pommel up toward his wrist-bones or wrist-joints. If he holds his hands too high, then cut with these Thwart Cuts up from below toward the knob of his elbows; thus it is done.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>