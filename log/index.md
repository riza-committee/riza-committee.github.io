---
layout: default
title: "devlog"
---

<div class="subscribe">
subscribe:
<a href="http://riza-committee.github.io/atom.xml">atom</a> |
<a href="http://riza-committee.github.io/rss.xml">rss</a> |
<a href="javascript:void(0)" onclick="return page.followPosts()">0net</a>
</div>

<ul class="posts">
  {% for post in site.posts %}
    <li class="post">
      <div class="meta">{{ post.date | date_to_string }}</div>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.content | split: '<cut />' | first }}
      <p class="read_more"><a href="{{ post.url }}">Read more..</a></p>
    </li>
  {% endfor %}
</ul>
