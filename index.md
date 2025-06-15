---
layout: home
title: Welcome to My Blog
---

<style>
  body {
    background-color: #87CEEB;
  }
</style>

Hi! I'm Prashant. I am working at Oracle on Machine Learning & AI . I write about tech, dev, finance & life.

<img src="/assets/images/pc.PNG" alt="My Setup" style="float: left; width: 200px; margin-right: 20px; margin-bottom: 10px;" />

## 🤖 LLM & AI Articles

{% for post in site.categories.LLM %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
- 
---


