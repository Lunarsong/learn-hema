---
category: 'Guards - Secondary'
manual: 'Meyer'
layout: page
title: Irongate / Eisenport
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
      <blockquote><p>The Irongate is done thus: stand with your right foot forward and hold your sword with the hilt in front of your knee with straight hanging arms, so that your point extends up toward your opponent's face. Thus you have your sword in front of you for protection like an iron door; for when you stand with your feet wide, so that your body is low, you can put off all cuts and thrusts from this position.</p></blockquote>

      <p>Unfortunately there is no illustration demonstrate this guard in the longsword manual but there is a similar guard in Rapier. One might think of it as an extended <a href="pflug">Plow</a> with the sword in front of the body.</p>

      <img class="card-image" src="/manuals/meyer/images/guards/eisenport-rapier-illustration.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>