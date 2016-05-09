---
layout: page
title: 听雨轩
tagline: 江南雨缠绵
---
{% include JB/setup %}


## 江南雨生的博客

<span>窗外雾霾扰扰，遮挡了远眺的目光，如恶魔般在大地间肆虐。 </span> 
<span>不远处高楼耸立，似乎在炫耀着繁华，殊不知在那繁华的背后，隐藏着无数的黑河。   </span>

### 博客列表

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




