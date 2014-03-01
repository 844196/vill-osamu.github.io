---
layout: page
title: 
---

{% include JB/setup %}


[![](https://c2.staticflickr.com/8/7362/9823661783_161f93c7c4_c.jpg)](http://www.flickr.com/photos/s083027/9823661783/)

## このサイトはなに？
[Log](http://844196.hatenablog.com/)からおさむ村に関するまとめ記事を移したものだよ。はちよん（[@84____](http://twitter.com/84____)）が管理しているよ。  
来るべき公式なWikiシステム導入までの繋ぎ程度に考えてね。

### 記事を書きたい人へ
おさむ村に関係していて、かつ、公共性が高いものについては掲載してもいいと考えています。  
（記事中に1個くらいおさむ村が登場すれば別にいいと思うよ）

書きたい場合は、はちよん（[@84____](http://twitter.com/84____)）に連絡して下さい。

## 最近の投稿

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_long_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
