---
category: 'Strikes - Chief / Principal'
manual: 'Meyer'
title: High Cut / Oberhau
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
      <p>In Meyer's system the High Cut (or Over Cut) is a vertical strike from above and is mentioned to also be the Scalp Cut (Scheitelhau), which is one of Liechtenauer's master cuts.</p>
      <blockquote><p>The High Cut is a straight cut directly from above, against your opponent’s head toward their scalp, therefore it is also called the Scalp Cut.</p></blockquote>

      <img style="width:400px;" class="card-image" src="/manuals/meyer/images/strikes/cutting_diagram_oberhau_meyer.png">


      <p>It is worth to note that within the Liechtenauer system the {{ page.title }} appears to include all cuts with a downward angle, be it straight down or diagonal.</p>
      <img style="width:400px;" class="card-image" src="/manuals/meyer/images/strikes/cutting_diagram_oberhau_liechtenauer.png">

      <p>In Meyer's system there is a divergence with the {{ page.title }} being a vertical cut while the <a href="zornhau">Wrath Cut / Zornhau</a> refers to diagonal cuts from above.</p>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>