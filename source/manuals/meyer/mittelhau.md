---
category: 'Strikes - Chief / Principal'
manual: 'Meyer'
title: Horizontal Cut / Mittelhau
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
      <p>The Middle or Traversing Strike can execute most effects the Wrathful Strike can, the difference is only that while the Wrathful Strike is a forceful high point, the Diagonal Traverse is brought full on. How the upper lines are traversed is shown in both illustration C (background) and illustration G (background). Such lines are also applicable to Dusack.
      </p>

      <img style="width:400px;" class="card-image" src="/manuals/meyer/images/strikes/cutting_diagram_mittelhau.png">

      <img class="card-image" src="/manuals/meyer/images/Meyer_1570_Longsword_C.jpg">

      <img class="card-image" src="/manuals/meyer/images/Meyer_1570_Longsword_G.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>