---
category: 'Strikes - Chief / Principal'
manual: 'Meyer'
title: Wrath Cut / Zornhau
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
      <p>The Wrathful Strike is a serious strike from your Right Shoulder, against your opponent’s left ear, or through their face or chest, consider how it’s done through two lines, with the lines drawn through the upper right and crosswise overtop one another.</p>

      <img style="width:400px;" class="card-image" src="/manuals/meyer/images/strikes/cutting_diagram_zornhau.png">

      <img class="card-image" src="/manuals/meyer/images/strikes/zornhau.gif">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>