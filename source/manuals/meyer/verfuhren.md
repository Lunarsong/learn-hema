---
category: '3. Handwork'
manual: 'Meyer'
layout: page
title: Deceiving / Verführen
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


      <p>Transcription:</p>
      <blockquote><p>This happens when you act as if you intended to lay on to one of your opponent's openings, but you don't do it, and instead deliver the stroke to another opening where you believe you can arrive most conveniently without harm.</p>

      <p>Various techniques fall under the category of deceiving, such as the <a href="krumphau">Squinting Cut</a> with the face, <a href="fehlen">failing</a>, <a href="verfliegen">flitting</a>, deceitful glancing, <a href="ablauffen">running off</a>, <a href="zucken">pulling</a> and the <a href="zirckel">Circle</a>, and others.</p>

      <p>Various deceptions not only with the sword but also with the body arise here. Thus there are as many versions of this as there are types and qualities of fighters, for it depends entirely on everyone's character and custom in combat: as one fights wrathfully, another circumspectly<, this one swift and fast, that one slowly, so also deceiving takes like form and is so carried out in the work.</p></blockquote>

    </div>
  </template>

  <script>
    Polymer({
      is: '{{ page.url | split:'/' | last | remove: '.html' }}-element',
    });
  </script>
</dom-module>