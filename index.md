---
layout: home
title: Welcome to My Blog
---

<style>
  body {
    background-color: #87CEEB; /* Sky Blue */
  }
  .profile-pic {
    float: left;
    width: 150px;
    height: 150px;
    margin-right: 20px;
    margin-bottom: 10px;
    border-radius: 50%;
    object-fit: cover; /* Prevents image distortion */
  }
  .contact-links {
    clear: left; /* Ensures it appears below the floated image */
    padding-top: 10px;
  }
  .contact-links a {
    margin-right: 10px;
    text-decoration: none;
  }
  .blog-section h2 {
    clear: both; /* Ensure blog section starts below floated elements */
    padding-top: 20px;
  }
  .blog-section h3 {
    margin-top: 1.5em;
  }
  .publications-section h2 {
    clear: both; /* Ensure section starts below floated elements */
    padding-top: 20px;
  }
  .publications-section ul {
    list-style-type: disc;
    padding-left: 20px;
  }
  .publications-section li {
    margin-bottom: 0.5em;
  }
</style>

<img src="/assets/images/pc.PNG" alt="Prashant C" class="profile-pic" />

Hi! I'm Prashant. I am working at Oracle on Machine Learning & AI . I write about tech, dev, finance & life.

<div class="contact-links">
  <p>
    Connect with me: <br />
    <a href="https://www.linkedin.com/in/prashant0231/" target="_blank">LinkedIn</a> |
    <a href="prashantchauhan23@gmail.com">Email</a>
  </p>
</div>

<div class="blog-section">



### 🤖 LLM & AI Articles
{% for post in site.categories.LLM %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
- 
---

### 🐍 Python Articles
{% for post in site.categories.Python %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
- 
---

<div class="publications-section">
## 📜 Publications and Conferences

<ul>
  <li>
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S152661251830553X" target="_blank">Modeling of defects in friction stir welding using coupled Eulerian and Lagrangian method</a> 
  </li>
</ul>
</div>

---


