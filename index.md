---
layout: page
title: 
---

{% include JB/setup %}

<div class="hero-unit" style=" background: url(https://v4s2.yimg.com/sk/3765/12857883384_aa8e908756_o.png); background-position: left; ">
<font color="white">
<h1 style="font-family: sans-serif">Osamu Server</h1>
<p>
うちのコミュではMinecraftのマルチサーバを立ててます<br>
これを呼んで　是非　参加してみて下さい<br>
大したことは　してないけどね<br>
</p>
</font>
<a class="btn btn-primary btn-large" href="http://ch.nicovideo.jp/osamu">サーバー管理者のブロマガを読む</a>
</div>


<div class="span7">
<h1>このサイトはなに？</h1>
<p>
<a href="http://844196.hatenablog.com/">Log</a>からおさむ村に関するまとめ記事を移したものだよ。はちよん（<a href="http://twitter.com/84____">@84____</a>）が管理しているよ。<br>
来るべき公式なWikiシステム導入までの繋ぎ程度に考えてね。
</p>


<h1>記事を書きたい人へ</h1>
<p>
おさむ村に関係していて、かつ、公共性が高いものについては掲載してもいいと考えています。<br>
（記事中に1個くらいおさむ村が登場すれば別にいいと思うよ）</p>
<p>
書きたい場合は、はちよん（<a href="http://twitter.com/84____">@84____</a>）に連絡して下さい。
</p>
</div>


<div class="span4">
<h1>最近の投稿</h1>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_long_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
</div>
