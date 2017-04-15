---
category: '1. Guards - Secondary'
manual: 'Meyer'
layout: page
title: Long Point / Langort
order: 2
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
      <p><blockquote>Stand with your Left foot forward, hold your Weapon with outstretched arms out in front of your face, so that you stand and point forward at your opponent’s face, and thus you stand in the Guard of the Long Point</blockquote></p>
      <img class="card-image" src="/manuals/meyer/images/guards/langort-illustration.jpg">

      <p>It is useful to note that in the Liechtenauer tradition Longpoint is also referred through Speaking Window, either as a concept for fighting, or an additional name for the guard. Transcript from <a href="http://wiktenauer.com/wiki/Pseudo-Peter_von_Danzig">Pseudo-Peter von Danzig</a>'s explanation of the Speaking Window:</p>
      <blockquote><p>Mark, you have heard before how you shall position yourself before the man with the sword in the Four Guards, and you shall fence therefrom. So shall you now also know the Speaking-Window, which is also a guard that you may well stand in, and the guard that is called the Long Point is the noblest and the best ward with the sword. Whoever correctly fences therefrom can force the man, that he must let you strike as you desire, and may not come to strikes and stabs himself before the point.</p>

      <p>Position yourself thus in the Speaking-Window: When you go to him with the pre-fencing, with whatever hew you then come on him (whether it be a Under or an Over-hew), then let the long point always shoot in to his face or his breast with the hew. Therewith you force him, so that he must parry you or bind on the sword, and when he thus has bound on, then remain strongly with the long edge on the sword and stand freely and see his business (what he will further fence against you). If he pulls off backwards from the sword, then follow after him with the point to the opening. Or, if he strikes around from the sword to the other side, then bind after his hew strongly above to his head. Or, if he will not draw off from the sword or strike around, then work with the Doubling (or otherwise with other techniques) thereafter as you find him Weak or Strong on the sword.</p>

      <p>And is also called the Speaking-Window. Mark, when you come close to him with the pre-fencing, then set your left foot before, and hold the long point with your arms against his face or his breast before you bind him on the sword, and stand freely and see what he will fence against you. If he then hews in to your head long above, then drive up and Wind against his hew with the sword in the Ox, and stab into his face. Or, if he hews to your sword and not to your body, then Change through and stab in to the other side. If he runs in and is high with his arms, then drive the Under-slice. Or, if he runs in through with wrestling and is low with his arms, then drive the arm wrestling. Thus you may drive all techniques from the Long Point.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>