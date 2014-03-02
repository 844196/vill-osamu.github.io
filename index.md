---
layout: top
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
<a class="btn btn-primary btn-large" href="/2014/02/09/新規向け概要/">さらに詳しく</a>
</div>


<div class="marketing">
<h1>すべてのクラフターたちのために構築されました</h1>
<p class="marketing-byline">多くの人たちに愛されているMinecraftの体験を、さらに素晴らしいものにしたい。<br>おさむ村は、そんな気持ちから始まりました。</p>


    <div class="row-fluid">
            <div class="span4">
                <img src="https://v4s2.yimg.com/sk/3737/12873768224_dd1d01a28e_b.jpg">
                <h2>24時間、365日、常時稼働。</h2>
                <p>アイディアはいつやって来るかわかりません。でも、おさむ村なら大丈夫。24時間365日常時稼働なので、あなたのアイディアをいつでも形にすることができます。</p>
            </div>
            <div class="span4">
                <img src="https://v4s2.yimg.com/so/7364/12872059035_231cb384b8_b.jpg">
                <h2>方向音痴（笑）も安心。</h2>
                <p>もし、おさむ村で道に迷っても問題ありません。動く地図は、あなたの今いる場所、向かっている方角、最寄りのランドマーク、友達がどこにいるかがひと目で分かります。</p>
            </div>
            <div class="span4">
                <img src="https://v4s2.yimg.com/sk/3758/12873843294_397808af04_b.jpg">
                <h2>スペースが余りました。</h2>
                <p>文月ちゃんはかわいいです！</p>
            </div>
    </div>


<h2>ホットニュース</h2><p style="color: #999">最新の情報をあなたに</p>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_long_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




</div>


<!--
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
-->
