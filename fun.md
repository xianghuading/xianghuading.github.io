---
title: 
layout: page
categories: media
---
My work keeps me tied to the computer most of time, so when I am not working, I really enjoy stepping away through hands-on making. I like creating things that are cute, beautiful and sometimes even practical, such as cooking and crocheting. 
They keep my hands busy, my head unwind from work and stay sane. By keeping my hands busy, they help me switch off from work, and stay sane.  

When the weather is nice, which is not so usual in Scotland, I also enjoy hiking wheven time allows.  
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
