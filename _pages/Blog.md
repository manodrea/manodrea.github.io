---
title: Thoughts, Journeys, & Favorite Things
permalink: /Blog/
layout: single
toc: true
toc_label: "Table of Contents"
image: /img/Barcelona.png/
author_profile: true
---

![](/img/KyotoTrees.jpg) 

> Welcome to my blog! I am particularly interested in botany and fragrant plants - I am creating a series of entries that I call "Ode to a Note". Each entry will explore a little history and some interesting factoids that I encounter in my research of botanical species that I, and many others, like to use to for fragrance or to just admire. Note that this space doubles as a journal, so information may be continually updated or corrected. Occasionally I may post opinion pieces (Thoughts), personal stories and photographs from my travels (Journeys), or just little things that I'm currently obsessing over (Favorite Things).

<h1>Latest Blog Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

---





***

