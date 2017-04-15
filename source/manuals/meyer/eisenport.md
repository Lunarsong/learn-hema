---
category: '1. Guards - Secondary'
manual: 'Meyer'
layout: page
title: Irongate / Eisenport
order: 5
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

      <p>Unfortunately there is no illustration demonstrate this guard in the longsword manual but there is a similar guard in Rapier. One might think of it as <a href="langort">Long Point</a> or an extended <a href="pflug">Plow</a> with the sword in front of the body.</p>

      <img class="card-image" src="/manuals/meyer/images/guards/eisenport-rapier-illustration.jpg">

      <p>It is useful to note that Meÿer's Irongate was most likely inspired from Italian traditions. An example can be found in Marozzo's "Greatsword", which has Porta di Ferro (Irongate).</p>

      <p>Porta di Ferro Alta (High Irongate):</p>
      <img class="card-image" src="/manuals/meyer/images/guards/Marozzo_Porta_di_Ferro_Alta.png">

      <p>Porta di Ferro Stretta (Narrow Irongate):</p>
      <img class="card-image" src="/manuals/meyer/images/guards/Marozzo_Porta_di_Ferro_Stretta.png">

      <p>When comparing with the Liechtenauer tradition, one could argue this is very similar to the Speaking Window, which is referenced within the <a href="langort">Longpoint</a>.</p>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>