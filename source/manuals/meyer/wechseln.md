---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Changing / Wechseln
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
      <blockquote><p>Changing demands an experienced combatant, for they who change in expertly and not at the right time only delays themselves and make themselves open without cause. But for they who are experienced in combat and know how to use changing, it is an artful work and appropriate to execute against those who only work toward the sword and not toward the body.</p>

      <p>Now changing is diverse: changing in the Onset from one side to another, changing before the Onset from one guard to another, also in the Onset to change through against the cut.</p>

      <blockquote><p>Thus in the Onset deliver a straight Wrath or High Cut from your right at your opponent's left side. If they cut at your sword and not your body, then in the cut let your point slip through underneath with crossed hands; step and cut long in to the other upper opening. But be careful that they do not catch you or plant their weapon upon you by chasing.</p>

      <p>Likewise in the Onset come into the Longpoint and extend it long in front of you. If they cut against your sword and intend to strike it out or wind, then let your point sink through underneath and work at their other side. If they slip after it and intend to parry, then change through again, either until you have an opening or else until you come upon a suitable work with which you can cut.</p>
      </blockquote>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>