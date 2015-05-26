---

layout: page
title: Ryan's Blog
tagline: Supporting tagline

---
{% include JB/setup %}

##最新日志
    
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<br /><br /><br /><br />


##关于这个博客

在2015年的9月开始，我就要去日本留学了。我相信这一次经历一定会是影响我一生的经历。因此我决定在这个博客上把我在接下来的所见、所闻、所学、所思完全记录下来.让自己有一个反省、思考的地方，也让自己可以温故而知新。

##About This Blog

From Sept. 2015, I will go to Japan for study. I believe that this experience must influence my life, so I decide to record what I see, hear, learn and think on this blog. 

##このブログについて

2015年9月から、日本へ留学に行くつもりです。この経験が一生を影響する経験を信じています。ですからこのブログで私の見ること、聞くこと、学ぶこと考えることをすべて記録することが決めています。


