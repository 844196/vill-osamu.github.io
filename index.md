---
layout: page
title: 
---

{% include JB/setup %}


[![](https://c2.staticflickr.com/8/7362/9823661783_161f93c7c4_c.jpg)](http://www.flickr.com/photos/s083027/9823661783/)

## このサイトはなに？
[Log](http://844196.hatenablog.com/)からおさむ村に関するまとめ記事を移したものだよ。

## 最近の投稿

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_long_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
