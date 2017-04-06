---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Circle / Zirckel
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


      <p>Transcription:</p>
      <blockquote><p>When you stand before your opponent in the bind and both of you have your swords overhead in the air, but neither will make themselves open before the other, then the Circle is an extremely good work to use. You shall do it thus:</p>

      <blockquote><p>Cut through from above with the short edge and crossed hands past their right side, so that your hands remain above your head, and in the cut cross your right hand well over the left so that you may well reach or graze their right ear with the short edge. But if they then slip with their arms down after your sword, then step with your right foot well sideways to the right or back and deliver a straight Scalp Cut at their head.</p></blockquote>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>