---
layout: default
---

# 欢迎来到我的技术博客

## 最新文章

{% for post in site.posts %}
  <article>
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <time>{{ post.date | date: "%Y-%m-%d" }}</time>
    <p>{{ post.excerpt }}</p>
  </article>
{% endfor %}
