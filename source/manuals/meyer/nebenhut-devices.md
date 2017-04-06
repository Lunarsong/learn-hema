---
category: '4. Devices / Stücke'
manual: 'Meyer'
layout: page
title: Side Guard / Nebenhut
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

      <h2>First Device</h2>
      <blockquote><p>From the Close Guard you will fence into the Arc Strike; as you have been struck to an opening when you hold yourself in the right Close Guard, then step springing with your right foot to his left well away from his strike, and strike with crossed hands above and behind his blade to his head, twitch nimbly (where you don’t want to wrench out to your left) above him with crossed hands and hit strongly with the outward flat from below to his left ear; however where he won’t strike, then fence such as you will learn from the Middle Guard following this.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>