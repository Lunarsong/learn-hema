---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Failing / Fehlen
order: 14
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
      <blockquote><p>Anyone can well deliver a failing attack, but only a well trained combatant knows how to execute it suitably at the proper time. Therefore if you wish to deliver a failing stroke advantageously such that you can gather another from it, then take care when you cut at an opening and your opponent seeks to parry you, that you do not let the cut connect, but run off and cut at another opening. For example:</p>

      <blockquote><p>In the Onset, come into right Wrath, and as soon as you can reach your opponent, then step and cut at their left ear as far as their sword, but before the cut connects, lift the pommel and let the blade run off by their left side without hitting and pull it around your head; then cut at their other side outside over their right arm at their head.</p></blockquote>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>