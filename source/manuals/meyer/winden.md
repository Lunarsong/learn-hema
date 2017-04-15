---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Winding / Winden
order: 17
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
      <blockquote><p>The word winding in proper German is Wenden [turning]. This work shall be done thus: when you havebound from your right against their left on your opponent's sword, then remain fast in the bind, and turn the foible of your blade in their head and back out, yet such that during this you always remain firm on their sword with the bind. It can be seen in this example:</p>

      <blockquote><p>If someone cuts at you from <a href="vom-tag">Vom-Tag</a>, then bind from your right with a <a href="zwerchhau">Zwerchhau</a> on their sword and as soon as it clashes, then push your pommel through under your right arm and thus turn the short edge in a flick inward at their head; and in all this remain hard on their sword with the slice. If they see the flick and parry, or if you can feel that they are going to fall down from the sword at your opening from above, then jerk the pommel back out from under your arm upward to your left and strike back with a short edge <a href="zwerchhau">Zwerchhau</a> at their left ear.</p></blockquote>
      </blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>