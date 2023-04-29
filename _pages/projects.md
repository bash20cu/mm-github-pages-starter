---
permalink: /Portfolio/projects/
title: "Projects"
excerpt_separator: "projects"
tags:
  - Projects
  - Django
  - AWS
  - Virtual
  - Network
  - Alura
  - Oracle
toc: false
toc_label: "My Table of Contents"
toc_icon: "cog"
---


Here are some of the projects I have worked on and completed:

{% assign sorted_posts = site.posts | sort: 'date' | reverse %}
<ul>
  {% for post in sorted_posts %}
    <li>
      <a href="{{ post.url }}" class="post-link" >{{ post.title }} </a>
      <p>Published on: {{ post.date | date: "%B %d, %Y" }}</p>
    </li>
  {% endfor %}
</ul>


