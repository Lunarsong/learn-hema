---
category: '2. Strikes - Secondary'
manual: 'Meyer'
title: Blind Cut / Blendthau
order: 4
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
      <blockquote><p>Bind your opponent from your right on his sword; in the bind, wind through below with your hilt or haft toward [your] left side. When your opponent tries to slip after the winding, then nimbly flick the foible, that is the point, at his head from your right at his left with crossed hands. Quickly wind back through, or wrench to your left side with the short edge; thus you have executed the Blind Cut. This Blind Cut is done in many ways; there will be more about it in the section on devices.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>