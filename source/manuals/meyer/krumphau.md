---
category: '2. Strikes - Master'
manual: 'Meyer'
title: Crooked Cut / Krumphau
order: 2
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
      <blockquote><p>This cut is executed thus: stand in the Wrath Guard with your left foot forward; if your opponent cuts at you, then step with your right foot well out from his stroke toward his left side; cut with the long edge and crossed hands against his cut, or across on his hands between his head and blade, and let the blade shoot well over his arm, as can be seen in Image D in the figures on the upper right.</p></blockquote>

      <img style="width:600px;" class="card-image" src="/manuals/meyer/images/strikes/krumphau-illustration.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>