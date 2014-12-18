---
layout: page
title: Practice Makes Perfect
tagline: --I MISS U
---
{% include JB/setup %}

## About me

    English name : Louis
    Chinese name : Zhenchao Gan
    school : Shanghai Jiao Tong Univ.
    email : zhenchaogan@hotmail.com
    github : github.com/gzc


## Work Experience
    Intel Asia-Pacific R&D Ltd.                 Nov.2014-Present

    
## Latest Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




