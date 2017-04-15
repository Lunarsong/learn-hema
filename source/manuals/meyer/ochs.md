---
category: '1. Guards - Core'
manual: 'Meyer'
layout: page
title: Ox / Ochs
order: 1
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

      <p>The Ox is the first posture (or guard) described by Meyer and is one of his chief postures. The Ox is the upper hanger, intended to defend the two upper (left and right) quarters of the body. He describes it thus:</p>

      <blockquote><p>The upper parts of the combatant are guarded with the Ox, which is two moded, right and left, thus one can stand in the Ox in two modes, namely the right and left modes.</p>

      <p>The right Ox is performed thus: stand with your Left Foot forward, holding the Sword with the hilt next to your head, high and on the right side, so that your forward point is directed against your opponent’s face. For the left Ox reverse this, namely stand with your right Foot forward, hold your hilt near your head on its left side as said above.</p></blockquote>

      <img class="card-image" src="/manuals/meyer/images/guards/ochs-illustration.jpg">

      <p>The Ox is also one of Liechtenauer's chief postures, which most likely influenced its inclusion in Meyer's chief postures.</p>

      <p>It may be useful to note the configuration of the hands in the position of the Ox, when comparing different descriptions and illustrations across the Liechtenauer tradition some describe the thumb being below the blade while others do not:</p>

      <p><strong>Pseudo-Peter von Danzig</strong>
      <blockquote>The first guard is called the Ox, position yourself thus with it: stand with your left foot before and hold your sword near your right side, with the hilt before your head so that your thumb is under the sword, and hang the point in against his face.</blockquote></p>

      <p><strong>Sigmund ain Ringeck</strong>
      <blockquote>The first guard is called the Ox; arrange yourself thusly: Stand with the left foot forwards and hold your sword near your right side with the hilt in front of your head, and let the point hang against the face.</blockquote></p>

      <p><strong>Jud Lew</strong>
      <blockquote>Position yourself in the Ox thus: stand with the left foot in front and hold your sword on your right side with the hilt in front of the head, so that the short edge stands against you, and hold the point thus against the face. Position yourself on the left side in the Ox thus: stand with the right foot before and hold your sword on your left side with the hilt in front of the head, so that the long edge stands against you, and hold the point thus against his face.</blockquote></p>

      <p>Derivative to the hand position is the angle of the blade itself. There are three edge configurations we can have for the Ox: vertical, horizontal or angled, each with some pros and cons.

      <li><strong>Vertical</strong> angle fails to protect to the hands against an oncoming cut. It is however easier to transition into some cuts through it.</li>
      <li><strong>Horizontal</strong> angle protects the hands better than a vertical angle and is a natural ending position when performing upper Thrawt cuts (Zwerchhaus). It does however leave some parts of the fingers exposes if gripped very close to the crossguard.</li>
      <li><strong>Angled</strong> configuration provides the most protection to the hands against cuts from above, though may feel somewhat more awkward to position at first.</li>
      </p>

      <p>It is the opinion of this page's writer (Shanee Nishry) that the angled configuration is the ideal and most protective - getting used to the angle is quite easy and once done Zwerchhaus will become naturally angled to reach to that position. However it is advised that you experiment with different the configurations and see how they work for you in protecting your hands and transitions into cuts. Remember that ideally you should always change your angle and grip to suit your needs and not strictly stick to a single configuration at all times.</p>



    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>