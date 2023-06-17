---
layout: page
title: 文章
---

**最近文章**

{% for post in site.posts limit:10 %}
<li class="post-list-in-index">
<small class="post-list-date-in-index">{{ post.date | date_to_string }}</small><a  href="{{ site.url }}{{ post.url }}" title="{{ post.title }}"> {{ post.title }}</a>
</li>
{% endfor %}


[**通过 RSS 订阅**](/feed.xml)
