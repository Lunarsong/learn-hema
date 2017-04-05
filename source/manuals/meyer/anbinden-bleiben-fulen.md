---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Binding / Remaining / Feeling - Anbinden / Bleiben / Fulen
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
      <blockquote><p>This is when the swords connect with one another. There are two kinds of remaining: the first is when the swords are held against one another to see what the opponent will execute and where they intend to attack their adversary. The other happens with striking, when you act as if you were pulling to gather for a stroke, only you simply flick back around and come back in with the short edge, where you cut first with the long edge.</p>

      <p>Note here the word 'feeling', which means testing, or perceiving, to find out whether they are hard or soft on your sword with their bind, etc.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>