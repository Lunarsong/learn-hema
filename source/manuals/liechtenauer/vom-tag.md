---
category: '2. Guards'
manual: 'Liechtenauer'
layout: page
title: Day / Vom Tag
order: 3
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

      <p>The third chief posture is the Day. Unlike the Ox and Plow, the Day is not a hanger and is not intended to protect the body; the day is a position where most attacks from above travel through. It is described thus:</p>

      <blockquote><p>Vom Tag is also called the High Guard <i>[Oberhut]</i> and is executed in the following manner: Stand with your left foot forward and hold your sword up over your head so that the point extends right upwards. Any atack that is delivered from above is said to be executed from the Day or High Guard; therefore this posture is called the Day.</p></blockquote>

      <img class="card-image" src="/manuals/meyer/images/guards/vom-tag-illustration.jpg">

      <p>To illustrate the concept that cuts from above travel through Vom-Tag, consider the following: position yourself in the right <a href="ochs">Ox</a> and perform a cut from above - if you've cut a long edge cut then most likely you have uncrossed your hands transitioning through Vom-Tag and proceeded cutting - doing this in a nice circular motion creates very fast transitions with powerful cuts. If you've cut a Zwerchhau, then you should obviously remain in the Ox position transitioning from left to right without going through Vom Tag.</p>

      <p><strong>Useful note: </strong>The Vom-Tag is described in various positions across the Liechtenauer tradition, all useful to know and recognize. The main differences is the position of the sword being either similiar to Meyer's, that is above the head, or over the shoulder, with the quillons by the ear on either side, or resting on the shoulder on either side. The second description makes it easy to see how uncrossing the hands from the right Ox transitions into the "right Vom-Tag".</p>

      <p>The different positions for Vom-Tag have various mechanical and psychological difference, for example a Wrath Strike [Zornhau] from the resting position can be quite quick, but will be more powerful from the other two positions. The over head position may be very intimidating to the opponent, but is also more difficult to perform, especially with full sparring gear. Transition to different cuts may be easier from one or another configuration, and some protect your hands better than others. Experiment with all options and learn to recognize the potentional transitions from them as it will help you choose your action from the positions and against one who takes these postures.</p>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>