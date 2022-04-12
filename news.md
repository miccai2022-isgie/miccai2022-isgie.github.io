---
title: News
layout: news
---

<ul>
{% for item in site.data.news.news %}
    <li> {{item}} </li>
{% endfor %}
</ul>