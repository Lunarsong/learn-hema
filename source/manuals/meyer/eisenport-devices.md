---
category: '4. Devices / Stücke'
manual: 'Meyer'
layout: page
title: Irongate / Eisenport
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

      <p>Although Meÿer refers to Irongate (Eisenport) here, it appears he actually means Crossed Guard (Schrankhut).</p>

      <h2>First Device</h2>
      <blockquote><p>This Iron Door is actually the Barrier Guard, from which you fence thus: if he strikes one from above, then drive thus out with crossed hands and catch his strike on the strong of your blade, just as he then takes his sword off your blade from this strike, then strike him (while his arms pull over himself) with a forceful upstrike to his arms, as soon as he tries to clear off then fence to his head.</p></blockquote>


      <h2>Second Device</h2>
      <blockquote><p>Note, displace his high strike as before, and just as the swords glide together then wind the short edge nimbly inward to his right ear, then wind again to his left side nimbly over him with your pommel through below, and with a back step strike long to the left of his head. However where he would fence to you from below, then fall from above with the long edge onto his sword into the Long Point. The Iron Door or Barrier Guard breaks out the Key, namely stab toward his face forcing him above himself, and then fence after him (just as he drives overhead) from below.</p></blockquote>
    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>