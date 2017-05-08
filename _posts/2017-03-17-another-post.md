---
layout: post
title:  "Another post"
date:   2017-03-13 19:09:48 +0100
tags: 
    - beatles
    - data
---

This is just another post. See how to include data inside your posts:

## Beatles Discography

<ul>
{% for album in site.data.beatles %}
    <li><b>{{ album.Name }}</b> (released on {{ album.Released }})</li>
{% endfor %}
</ul>

<script>
   (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
   (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
   m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
   })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');
 
   ga('create', 'UA-98738947-1', 'auto');
   ga('send', 'pageview');
 
 </script>
