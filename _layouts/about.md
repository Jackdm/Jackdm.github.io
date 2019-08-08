---
layout: post
title: "About"
author: "Jackdm"
permalink: /about/
---
<div class="post">
  <div class="post-info">
    <span>Written by</span>
    {% if page.author %}
        {{ page.author }}
    {% else %}
        {{ site.author.name }}
    {% endif %}

    {% if page.date %}
      <br>
      <span>on&nbsp;</span><time datetime="{{ page.date }}">{{ page.date | date: "%B %d, %Y" }}</time>
    {% endif %}
  </div>

  <h1 class="post-title">{{ page.title }}</h1>
  <div class="post-line"></div>

  {{ content }}

</div>

<div class="pagination">
  {% if page.next.url %}
    <a href="{{ page.next.url | prepend: site.baseurl }}" class="left arrow">&#8592;</a>
  {% endif %}
  {% if page.previous.url %}
    <a href="{{ page.previous.url | prepend: site.baseurl }}" class="right arrow">&#8594;</a>
  {% endif %}

  <a href="#" class="top">Top</a>
</div>

Seventeen years old. I make cool things.

This site is where you can find all of my blog posts, project logs, and other stuff.

Below are links to my other stuff on the web.

email: [jack@directmessagellc.com](mailto:jack@directmessagellc.com)

instagram: [instagram.com/Jackdm](https://instagram.com/Jackdm)

twitter: [twitter.com/JackDMcCoy](https://twitter.com/JackDMcCoy)

github: [github.com/Jackdm](https://github.com/Jackdm)

hackaday (the blog has the same projects as posted there, but in case you're interested): [https://hackaday.io/jackdm](https://hackaday.io/Jackdm)

resume (most updated copy): [click here to request access](https://docs.google.com/document/d/1Sg2tYXP1_FfZcsseL8wP_GC9u0bvUY4th15yb8D04A0/edit?usp=sharing)
