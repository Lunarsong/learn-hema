---
category: 'Strikes'
manual: 'Meyer'
title: Low Cut / Unterhau
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
      <p>This you execute thusly, strike so that you move into the Right Ox and thus can bring your opponent fencer into range, and step to strike from below traversing above into their left arm, while coming into position with the hilt high above your head, and thus complete. Regarding this, see the figures fighting against the left in the background of illustration B.
      </p>

      <img style="width:400px;" class="card-image" src="/manuals/meyer/images/strikes/cutting_diagram_unterhau.png">

      <img class="card-image" src="/manuals/meyer/images/Meyer_1570_Longsword_B.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>