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

<strong>Exciting News for Authors and Publishers!</strong> I'm currently accepting selected books for review. If you're looking for an honest review and your book fits my preferred genres, I'd be delighted to consider it. Please visit my <a href="/book-review-policy/">Book Review Policy</a> page for full details.