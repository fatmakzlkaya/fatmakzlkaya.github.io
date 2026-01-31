---
layout: default
title: "Checkered Notes"
---

<h2>Quick Access Categories 🚀</h2>
  <div class="category-container">
  <div class="category-card">
    <h3>🖥️ Linux</h3>
    <p>Notes on AI algorithms and data science.</p>
    <a href="{{ '/machine-learning/' | relative_url }}">Explore »</a>
  </div>
  <div class="category-card">
    <h3>🛜 Networking</h3>
    <p>Notes on AI algorithms and data science.</p>
    <a href="{{ '/machine-learning/' | relative_url }}">Explore »</a>
  </div>
  <div class="category-card">
    <h3>📰 News and More</h3>
    <p>The latest developments and analysis from the tech world.</p>
    <a href="{{ '/news/' | relative_url }}">Explore »</a>
  </div>
</div>

<h2>Latest Post</h2>

{% assign latest = site.pages | sort: "date" | reverse %}
{% for post in latest %}
  {% if post.path contains "machine-learning/" %}
  <div class="post-card">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
  </div>
  {% break %}
  {% endif %}
{% endfor %}
