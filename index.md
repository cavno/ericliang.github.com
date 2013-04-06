---

layout: page
title: 
tagline: You never know what you don't know, eh?
author-intro: <br/>
  I'm <a href="/">Eric Liang</a>, I'm a(n)
  <ul>
  <li>Life traveler<br/>
  enjoy running, swimming, hiking and horse riding</li>
  <li>Hacker<br/>
  hack everything interesting</li>
  <li>Multiple lanaguages programmer<br/>
  with C/C++, Erlang, Java and <a href="golang.org">Go</a> !</li>
  <li>IM technologist<br/>
  on serveral open sourced <a href="xmpp.org">XMPP</a> projects and <a href="">beyond</a></li>
  <li>Amateur researcher<br/>
  on distributed system and artifical intelligence</li>
  </ul>  
  Follow me at <a href="http://weibo.com/iyile">Weibo</a> or <a href="http://github.com/ericliang">GitHub</a>. More information, check <a href="/private/cv.html">here</a>.

---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
