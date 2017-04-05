---
category: '2. Strikes - Secondary'
manual: 'Meyer'
title: Plunge Cut / Sturtzhau
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
      <blockquote><p>Although this cut is a High Cut, and so considered because there is not much difference between the two, yet this is called the Plunge Cut because in cutting through, it always plunges over above, so that the point comes against the opponent’s face in the Ox; and it is most used in the Approach or Onset.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>