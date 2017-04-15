---
category: '1. Guards - Core'
manual: 'Meyer'
layout: page
title: Fool / Alber
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

      <p>The Fool is the fourth and last chief posture described by Meyer. It is described thus:</p>
      <blockquote><p>Stand with your left foot forward and hold your sword with the point extended toward the ground in front of you before your forward foot, such that the short edge lies above and the long edge below.</p></blockquote>

      <img class="card-image" src="/manuals/meyer/images/guards/alber-illustration.jpg">

      <p>The Fool is perhaps the most unusual of the core guards and we don't get a lot to work with it. It is unlike the others, in that it is not a hanger which defends the combatant (as the Ox and Plow), nor is it a position where one truly cuts off from (Day [Vom-Tag], Changer [Wechsel], Side Guard [Nebenhut]). One could view the Fool as two things:

      <li>The natural ending position of a descending cut.</li>
      <li>An invitation for the opponent to strike.</li>
      </p>

      <p>The first is quite obvious and needs no more explanation, while the second is more interesting. Meyer says the following of the Fool:</p>
      <blockquote><p>[...] from this Stance no proper stroke can be readily achieved, one just uses them to gain an opening against the opponent through displacements to block strikes, which can be used to measure a Foolish and naive person who is not ready for counterstrikes to be struck against them.</p></blockquote>

      <p>This hints us that the Fool is intended to displace strikes and follow with a counter. This falls in line with the Liechtenauer glosses' description of the Traveling After (Chasing) and Slicing Off, which gives us insight on how the Fool may be used:</p>

      <p><strong>Pseudo-Peter von Danzig - Traveling After</strong>
      <blockquote><p>Here mark a good Travelling-after on the sword from Under-hewing:</p>

      <p>Mark, when you fence against him from Under-hewing, or from the slashing, or lie against him in the guard that is called Fool, if he then falls with his sword on yours before you therewith come up, then remain thus with your sword below on his and heave upwards. If he then Winds on the sword with the point into your face or breast, then do not let him off from the sword, and follow him thereafter, and work in with the point to the next opening. Or, if he strikes around from the sword, then follow him or Travel-after with the point as before.</p></blockquote>

      <p><strong>Pseudo-Peter von Danzig - Slicing Off</strong>
      <blockquote>Gloss: Mark, that is what you shall drive when one binds on your sword strongly above, or falls thereon, and undertake it thus: when you fence-to with the Under-hewing or with the slashing, or lie against him in the guard Fool, if he then falls with his sword on yours (before you come up therewith), then remain below on his sword and heave upwards with the short edge fast. If he then presses your sword downwards fast, then slash off from his sword from below on his blade with your sword behind yourself, and hew in to the other side on his sword’s blade quickly again, above into his mouth.</p>

      <p>Another: When you fence-to him with Under-hewing, or lie in the guard Fool, if he then falls with the sword on yours nearby the hilt (before you come up therewith), so that his point goes out to your right side, then drive up nimbly with your pommel over his sword and strike with the long edge to his head. Or, if he binds on your sword so that his point goes out to your left side, then drive with your pommel over his sword and strike in with the short edge to his head. That is called the Snapping.</p></blockquote></p>

      <p>These examples show us ways we can deflect or slice through an opponent's stroke from the posture of the Fool, combined with the description of the <a href="nachreisen>Chasing</> we can gather how it used as an invitation to an attack with a prepared counter.</p>

</blockquote></p>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>