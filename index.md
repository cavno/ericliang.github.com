---

layout: page
title: 
tagline: You never know what you don't know, eh?
author-intro: <br/>
  I'm <a href="/">Eric Liang</a>
  <ul>
  <li>I'm a life traveler<br/>
  enjoy running, swimming, hiking and horse riding</li>
  <li>I'm a hacker<br/>
  hack everything interesting</li>
  <li>I'm a multiple lanaguages programmer<br/>
  with C/C++, Erlang, Java and <a href="golang.org">Go</a> !</li>
  <li>I'm an IM technologist<br/>
  on serveral open sourced <a href="xmpp.org">XMPP</a> projects and <a href="">beyond</a></li>
  <li>I'm an amateur researcher<br/>
  on distributed system and artifical intelligence</li>
  </ul>  
  For more information, check <a href="/private/cv.html">here</a>.

---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
