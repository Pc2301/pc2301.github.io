---
layout: default
title: 
---

<style>
  .top-name {
    text-align: center;
    font-size: 28px;
    font-weight: bold;
    margin-top: 20px;
  }
</style>

<div class="top-name">Prashant Chauhan</div>


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
    clear: left;
    padding-top: 10px;
  }
  .contact-links a {
    margin-right: 10px;
    text-decoration: none;
  }
  .blog-section h3,
  .publications-section h2 {
    clear: both;
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

Hi, I'm Prashant!
I currently work at Oracle Bangalore, where I focus on machine learning , large language models, natural language processing and software development. Outside of work, I'm passionate about finance, personal growth, and life lessons—and this blog is where I share insights and stories across all these areas.
<div class="contact-links">
  <p>
    Connect with me:<br />
    <a href="https://www.linkedin.com/in/prashant0231/" target="_blank">LinkedIn</a> |
    <a href="mailto:prashantchauhan23@gmail.com">Email</a>
  </p>
</div>

<div class="blog-section">
  {% assign llm_posts = site.categories.LLM %}
  {% if llm_posts and llm_posts.size > 0 %}
    <h3>🤖 LLM & AI Articles</h3>
    <ul>
      {% for post in llm_posts %}
        <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
      {% endfor %}
    </ul>
  {% endif %}

  {% assign python_posts = site.tags.Python %}
  {% if python_posts and python_posts.size > 0 %}
    <h3>🐍 Python Articles</h3>
    <ul>
      {% for post in python_posts %}
        <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
      {% endfor %}
    </ul>
  {% endif %}
</div>

<div class="publications-section">
  <h3>📜 Publications and Conferences</h3>
  <ul>
    <li>
      <a href="https://www.sciencedirect.com/science/article/abs/pii/S152661251830553X" target="_blank">
        Modeling of defects in friction stir welding using coupled Eulerian and Lagrangian method
      </a>
    </li>
  </ul>
</div>
