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
<h1>すべてのクラフターのために構築されました</h1>
<p class="marketing-byline">多くの人たちに愛されているMinecraftの体験を、さらに素晴らしいものにしたい。<br>おさむ村は、そんな気持ちから始まりました。</p>


    <div class="row-fluid">
            <div class="span4">
                <img src="https://v4s2.yimg.com/sk/3829/12878940593_a827868d95_b.jpg">
                <h2>24時間、365日、常時稼働。</h2>
                <p>アイディアはいつやって来るかわかりません。でも、おさむ村なら大丈夫。24時間365日常時稼働なので、あなたのアイディアをいつでも形にすることができます。</p>
            </div>
            <div class="span4">
                <img src="https://v4s2.yimg.com/so/7364/12872059035_231cb384b8_b.jpg">
                <h2>方向音痴（笑）も安心。</h2>
                <p>もし、おさむ村で道に迷っても問題ありません。動く地図なら、あなたの今いる場所、向かっている方角、最寄りのランドマーク、友達がどこにいるかがひと目で分かります。</p>
            </div>
            <div class="span4">
                <img src="https://v4s2.yimg.com/sk/3758/12873843294_397808af04_b.jpg">
                <h2>文月ちゃんかわいい！('ω')✌</h2>
                <p>しゅっせきばんごうにじゅうきゅう、ふみづきだよ～！</p>
                <a class="btn btn-small" href="http://goo.gl/il2Hre">さらに詳しく »</a>
            </div>
    </div>

<h2>ホットニュース</h2><p style="color: #999">最新の情報をあなたに</p>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_long_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
</div>
