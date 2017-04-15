---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Doubling / Doplieren
order: 11
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
      <blockquote><p>This is to make a cut or technique double in this way:</p>

      <blockquote><p>Cut first from your right to their ear; at once when the swords clash together, push your pommel through under your right arm; go up at the same time with both arms and strike them with the short edge behind their blade on their head.</p></blockquote>

      <p>This handwork is called doubling, because through it a cut is doubled or executed twice, first with the long edge, then with the short edge.</p>
      </blockquote>

      <p>It is worth to note that in the Liechtenauer tradition there is also a Duplieren and Pseudo-Peter von Danzig explains the strike is done in two ways after the initial bind, one with the long edge and crossed hands and the other with the short edge:</p>

      <blockquote><p>Mark, when he hews above to you from his right shoulder: then hew also from your right with him, likewise above strongly to the head. If he parries and remains Strong on the sword, then drive up Meanwhile with your arms, and thrust your sword’s pommel with your left hand under your right arm, and strike in with the long edge with crossed arms, behind his sword’s blade on his head.</p></blockquote>

      <img class="card-image" src="/manuals/meyer/images/handwork/PPvD_duplieren_1.jpg">

      <blockquote><p>Mark, if he hews you with the long edge in to your head from above his left shoulder, and you do likewise, if he then remains Strong on the sword again, then quickly drive up with your arms and strike in with the short edge, behind his sword’s blade on his head.</p></blockquote>

      <img class="card-image" src="/manuals/meyer/images/handwork/PPvD_duplieren_2.jpg">

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>