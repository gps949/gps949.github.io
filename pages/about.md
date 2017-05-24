---
layout: page
title: About
description: The best is yet to be
keywords: 小北极星, gps949
comments: true
menu: 关于
permalink: /about/
---

人生是一场猝不及防的旅程

如果不去否认，则拥有无限的可能性

只要保持好奇心，未接触过、没有经验其实反而是一件好事

更多的未知意味着更多的可待发现，让我们去思考

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}


