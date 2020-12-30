---
title: Thoughts, Journeys, & Favorite Things
permalink: /Blog/
layout: single
toc: true
toc_label: "Table of Contents"
image: /img/Barcelona.png/
author_profile: true
---

> Welcome to my site's blog. I plan to using this platform to start an informational blog. I am particularly interested in botanical and perfume history so I plan to create a series of entries that I call "Ode to a Note". Each entry will explore a little history and list of factoids of botanical notes that I like to use, with a little personal commentary. 

<h1>Latest Posts</h1>

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

