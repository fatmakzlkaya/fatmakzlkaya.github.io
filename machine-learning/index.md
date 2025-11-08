---
layout: default
title: "Machine Learning"
---

<h2>🤖 Machine Learning Notes</h2>
<p>Explore experiments, concepts, and guides on AI and data-driven systems.</p>

<h2>📘 Latest Posts</h2>

{% for post in site.pages %}
  {% if post.path contains "machine-learning/" and post.path != "machine-learning/index.md" %}
  <div class="post-card">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
  </div>
  {% endif %}
{% endfor %}
