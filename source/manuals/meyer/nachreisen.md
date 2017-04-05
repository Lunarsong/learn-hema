---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Chasing / Nachreisen
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
      <blockquote><p>This is a particularly good handwork, and he who is very skillful in it and knows well how to use it many properly be pr aised as a master.</p>

      <p>The chasing is executed thus: if your opponent cuts with their weapon either too far up or down, or too far out to the side, then you rush after them at their opening and thus prevent their cut from coming to completetion; for this may properly be used against those who fight with their cuts sweeping wide around them.</p>

      <blockquote><p>When an opponent is fighting with you, then observe in which part they hold their sword. Now if they hold it in the right Ox, that is in the upper right quarter, then the moment they take their sword away from there to change to the other side, or simply pulls up for the stroke, you shall cut in quickly and skillfully, using those cuts and techniques from which you can at once achieve a parry.</p>

      <p>Now if they attack from the lower guards (whether they fight from the left or right side), then as soon as they go up, see that you pursue them at once under their sword skillfully with the long edge and strike to the nearest opening.</p></blockquote>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>