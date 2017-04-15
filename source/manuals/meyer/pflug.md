---
category: '1. Guards - Core'
manual: 'Meyer'
title: Plow / Pflug
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

      <p>The Plow is the second guard described and is the lower hanger, intended to defend the two lower (left and right) quarters of the combatant. It is described thus:</p>

      <blockquote><p>The low parts are guarded with the Plough, whose two modes are similar figures for two sides, the right and the left, and so are named the Right and Left Plough. Both are in essence merely the position of a thrust from below.</p>

      <p>The Right Plough is described as follows, stand with your right foot forward, hold your weapon with the hilt near your forward knee and your point pointing in your opponent’s face, as if you intend to stab him from below. While you are in the Right Plough, step forward with the Left foot and stand similarly to be in the Left Plough.</p></blockquote>

      <img class="card-image" src="/manuals/meyer/images/guards/pflug-illustration.jpg">

      <p>The Plow is also Liechtenauer's second chief posture and it may be interesting to note some of the differences between Meyer's and Liechtenauer's Plow, mainly that Meyer describes the sword as being held near the front knee, while the Liechtenauer's tradition describes it at the opposite side:</p>

      <p><strong>Pseudo-Peter von Danzig</strong>
      <blockquote></p>This is the second guard:</p>
      <p>Mark, the other guard is called the Plow, there position yourself thus with it: stand with your left foot before and hold your sword with crossed hands, with the pommel below you near your right side on your hip, so that the short edge is above and the point stands in against his face.</p>

      <p>Mark, on the left side position yourself thus in the Plow: stand with your right foot before and hold your sword near your left side, with the pommel below you on your hip, so that the long edge is above and the point stands in against the face. That is the Plow on both sides.</p></blockquote></p>

      <p><strong>Sigmund ain Ringeck</strong>
      <blockquote>The second guard is called the plow; arrange yourself thusly: Stand with the left foot forward and hold your sword with crossed hands near your right side over your knee such that the point stands against the face.</blockquote></p>

      <p><strong>Jud Lew</strong>
      <blockquote>The second guard is called the Plow. Position yourself with\ it thus: set the left foot fore and hold your sword under you with crossed hands on your right side, with the pommel near your right hip, so that the short edge is above and the point stands before you against the face of the man. On the left side position yourself in the Plow thus: set the right foot fore and hold your sword under you near your left side, on your left hip, so that the long edge is turned above and the point stands upwards against the face of the man.</blockquote></p>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>