---
title: Joachim Meÿer
---

<link rel="import" href="/bower_components/polymer/polymer.html">
<link rel="import" href="shared-styles.html">

<dom-module id="main-element">
  <template>
    <style include="shared-styles">
      :host {
        display: block;

        padding: 10px;
      }
    </style>

    <div class="card">
      <h1>{{ page.title }}</h1>
      <p>These pages include resources from Joachim Meÿer's book "The Art of Combat".</p>

      <img class="card-image" src="/manuals/meyer/images/Meyer_1570_Cover.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: 'main-element',
    });
  </script>
</dom-module>