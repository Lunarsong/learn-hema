---
category: 'Strikes'
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
      <p>The Over Strike is a strong strike directly from Above, against your opponent’s head or scalp, therefore it is also called Vertex Strike.</p>

      <img style="width:400px;" class="card-image" src="/manuals/meyer/images/strikes/cutting_diagram_oberhau.png">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>