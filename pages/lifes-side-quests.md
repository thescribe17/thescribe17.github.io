---
permalink: /lifes-side-quests/
layout: page
title: "Life's Side Quests"
subtitle: "The other things I love to do"
---

The headings on this page include:
* TOC
{:toc}

On this page you will find subjects NOT related to reading, writing and publishing. I may or may not add more topics at a later date depending on my ever changing interests (sometimes referred to as current obsession).

## Posts on Gaming

<ul>
  {% assign posts = site.categories.gaming %}
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

## Posts on Technology

<ul>
  {% assign posts = site.categories.technology %}
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

## Posts on Genealogy

<ul>
  {% assign posts = site.categories.genealogy %}
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

## Posts on Movies

<ul>
  {% assign posts = site.categories.movies %}
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

## Posts on Craft

<ul>
  {% assign posts = site.categories.craft %}
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

