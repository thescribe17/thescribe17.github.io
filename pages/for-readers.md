---
permalink: /for-readers/
layout: page
title: "For Readers"
subtitle: "Book Reviews and Author Interviews"
---

The headings on this page include:
* TOC
{:toc}

## Author Interviews

<ul>
  {% assign posts = site.categories.author-interview %}
  {% if posts and posts.size > 0 %}
    {% for post in posts %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <span>({{ post.date | date: "%Y-%m-%d" }})</span>
      </li>
    {% endfor %}
  {% else %}
    <li>No author interviews have been posted yet.</li>
  {% endif %}
</ul>

## Book Reviews

<ul>
  {% assign posts = site.categories.book-review %}
  {% if posts and posts.size > 0 %}
    {% for post in posts %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <span>({{ post.date | date: "%Y-%m-%d" }})</span>
      </li>
    {% endfor %}
  {% else %}
    <li>No book reviews have been posted yet.</li>
  {% endif %}
</ul>

## Book Review Policy

<p>
  I write reviews for all the books I read. However, due to life's challenges, I haven't been able to read over recent years. However, my circumstances have changed and I have started writing again and intend to start reading again too. 
</p>

<p>  
  When I'm ready I will start offering book reviews for authors again. Here's my <a href="/book-review-policy/">Book Review Policy</a>.
</p>
