---
title: "People"
layout: splash
header:
  overlay_image: /assets/images/home.jpg
permalink: /people/index.html
date: 2018-01-07

gallery:
  - url: /assets/images/liyanzhi.png
    title: 'Yanzhi Li (David)'
    type: 'professor'
    bio: '/yanzhili/'
  - url: /assets/images/biyingshou.png
    title: 'Biying Shou'
    type: 'professor'
    bio: '/biyingshou/'
  - url: /assets/images/yuyang.png
    title: 'Yu Yang'
    type: 'professor'
    bio: '/yuyang/'
  - url: /assets/images/students/Dong Junyi.jpg
    title: "Dong Junyi"
    type: 'student'
  - url: /assets/images/students/Fu Qiaochu.jpg
    title: "Fu Qiaochu"
    type: 'student'
  - url: /assets/images/students/He Xing.jpg
    title: "He Xing"
    type: 'student'
  - url: /assets/images/students/Lu Jialiang.jpg
    title: "Lu Jialiang"
    type: 'student'
  - url: /assets/images/students/Wu Tongwen.jpg
    title: "Wu Tongwen"
    type: 'student'
  - url: /assets/images/students/Zheng Zhenhang.jpg
    title: "Zheng Zhenhang"
    type: 'student'
---

{% for g in page.gallery %}
<div class="member"><img class="{{g.type}}" src="{{g.url | relative_url}}"/><h3><a href="{{g.bio | relative_url}}">{{g.title}}</a></h3></div>
{% endfor %}
