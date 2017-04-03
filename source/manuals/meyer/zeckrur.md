---
category: 'Strikes - Secondary'
manual: 'Meyer'
title: Flick [Schneller] or Tag-Hit [Zeckrur]
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
      <blockquote><p>The flick or Tag-Hit is not actually delivered as a cut, but is rather flicked; it is executed in the middle of combat when one has occasion, namely when you make your weapon snap at your opponent from above or from either side or from below with the flat or foible of the blade, or flick it in an arc over or under his blade.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>