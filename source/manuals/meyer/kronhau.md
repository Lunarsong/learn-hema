---
category: '2. Strikes - Secondary'
manual: 'Meyer'
title: Crown Cut / Kronhau
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
      <blockquote><p>This is executed thus: when you stand in the Plow or else lay on up from below from some posture (concerning which I have spoken in the previous chapter), and your opponent cuts at you from above, then go up with horizontal quillons and catch his stroke in the air on your shield or quillon bar; and as soon as it clashes, push the pommel quickly upward and strike him with the short edge behind his blade on his head; thus have you correctly executed the Crown Cut.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>