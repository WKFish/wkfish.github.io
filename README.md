---
layout: page
title: 文章
---
这是 WKFish 的博客，主要发布科技为主的内容。
这里正在搭建中，所以你暂时看不到任何东西。

[**我的 PolitiScales 测试结果**](https://politiscales.party/results?bTA9NTcmbTE9MjEmajE9MjkmajA9MzMmcDA9NTAmcDE9NSZjMD01NSZmZW1pPTM4JmMxPTUmczE9MzMmczA9MzMmYjE9MTcmYjA9NjImZTA9MzEmZTE9MzYmdDE9MjQmdDA9Mjk=)

**最近文章**

{% for post in site.posts limit:10 %}
<li class="post-list-in-index">
<small class="post-list-date-in-index">{{ post.date | date_to_string }}</small><a  href="{{ site.url }}{{ post.url }}" title="{{ post.title }}"> {{ post.title }}</a>
</li>
{% endfor %}
