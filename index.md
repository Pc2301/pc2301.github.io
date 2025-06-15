---
layout: home
title: Welcome to My Blog
---

Hi! I'm Prashant. Welcome to my blog where I write about tech, dev, finance & life.

<img src="/assets/images/pc.PNG" alt="My Setup" width="600" />

## 🤖 LLM & AI Articles

{% for post in site.categories.LLM %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
- 
---


