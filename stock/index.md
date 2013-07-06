---
title: 股票知识
layout: page
---
<ul class="listing">
<li class="listing-seperator" id="{{ tag[0] }}">第一章 谈道理</li>
{% for post in site.tags.daoli %}
  <li class="listing-item">
  <time datetime="{{ post.date | date:"%Y-%m-%d" }}">{{ post.date | date:"%Y-%m-%d" }}</time>
  <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
<ul class="listing">
<li class="listing-seperator" id="{{ tag[0] }}">第二章 看市场</li>
{% for post in site.tags.shichang %}
  <li class="listing-item">
  <time datetime="{{ post.date | date:"%Y-%m-%d" }}">{{ post.date | date:"%Y-%m-%d" }}</time>
  <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>