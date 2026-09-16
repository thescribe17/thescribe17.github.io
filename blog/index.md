---
layout: default
title: Blog
subtitle: Updates, news, and writing reflections
pagination:
  enabled: true
---

<h1>Blog</h1>

{% if paginator.posts %}
  <ul class="posts">
    {% for post in paginator.posts %}
      <li>
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.excerpt }}</p>
      </li>
    {% endfor %}
  </ul>

  <div class="pagination">
    {% if paginator.previous_page %}
      <a href="{{ paginator.previous_page_path }}">Previous</a>
    {% endif %}

    {% if paginator.next_page %}
      <a href="{{ paginator.next_page_path }}">Next</a>
    {% endif %}
  </div>

{% else %}
  <p>No posts found.</p>
{% endif %}
