---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Winding Through / Durchwinden
order: 18
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
      <blockquote><p>When you have bound with a <a href="zwerchhau">Zwerchhau</a> and wound the short edge in at your opponent's head, then step through with your right foot between you and them, toward your opponent's right side, and at the same time wind through with your haft under their blade to your left side and send your pommel outside over their right arm. Step back with your right foot and with this, wrench down on your right side and strike with the long edge on their head. Thus have you not only wound through, but caught over with the pommel.</p>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>