---
category: 'Strikes - Master'
manual: 'Meyer'
title: Squinting Cut / Schielhau
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
      <blockquote><p>The Squinting Cut is also a High Cut, but is so named because it is delivered as if with a bit of a squint. It is done thus: Position yourself in the guard of the Day or Wrath (concerning which I have spoken in Chapter 3), with your left foot forward; when he cuts at you, then cut in return, but in the stroke, turn your short edge against his stroke, and strike in at the same time as your opponent, palm away from his sword; step with your right foot well to his left side, and with this, nimbly take your head out of the way. Thus you have executed it correctly against him, and you stand as shown by the large figure on the left in Image G.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>