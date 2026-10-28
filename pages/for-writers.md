---
permalink: /for-writers/
layout: page
title: "For Writers"
subtitle: "Writing and Publishing Tips and Resources"
---

The headings on this page include:
* TOC
{:toc}

Writing is one of the most rewarding creative pursuits, but it can also be one of the most challenging. Whether you're writing for children, young adults, or adults, every story begins with an idea and grows through dedication, learning, and persistence. Creating believable characters, compelling plots, and immersive worlds takes time, practice, and a willingness to keep improving your craft.

Along the way, you'll experience moments of self-doubt, excitement, frustration, and triumph. The good news is that every word you write helps you grow as an author, and every finished project is an achievement worth celebrating.

<strong>Exciting News for Authors and Publishers!</strong> I'm currently accepting selected books for review. If you're looking for an honest review and your book fits my preferred genres, I'd be delighted to consider it. You'll find the link below.

To help support writers at every stage of their journey, I've collected articles on writing, editing, publishing, and other topics that can help turn a manuscript into a finished book.

If you discover a broken link or run into any issues while browsing the site, please use the contact form to let me know so I can fix it.

## Free Book Reviews for Authors and Publishers

Interested in a free book review? Please visit my <a href="/book-review-policy/">Book Review Policy</a> page for full details.

## Posts on Writing

<ul>
  {% assign posts = site.categories.writing %}
  {% if posts and posts.size > 0 %}
    {% for post in posts %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <span>({{ post.date | date: "%Y-%m-%d" }})</span>
      </li>
    {% endfor %}
  {% else %}
    <li>No writing posts have been posted yet.</li>
  {% endif %}
</ul>

## Posts on Publishing and Editing

<ul>
  {% assign posts = site.categories.publishing %}
  {% if posts and posts.size > 0 %}
    {% for post in posts %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <span>({{ post.date | date: "%Y-%m-%d" }})</span>
      </li>
    {% endfor %}
  {% else %}
    <li>No publishing or editing posts have been posted yet.</li>
  {% endif %}
</ul>

## Recommended Software

<p>These links are <strong>NOT</strong> affiliate links. I recommend them, because I use them myself and like them.</p>
<ul>
<li><a href="http://www.rsingermanson.com/html/the_snowflake.html">Snowflake Process of Writing a Novel</a> - for planning your novel. Purchase the software or use the manual method. I've done both, and they both work wonders.</li>
<li><a href="http://www.spacejock.com/yWriter6.html">yWriter 6</a> - I use this software for every project I write. It's brilliant!</li>
<li><a href="https://tiddlywiki.com/" target="_blank" rel="noopener">Tiddlywiki</a> - a free notebook for all your planning and research notes. I love it.</li>
<li><a href="https://calibre-ebook.com/">Calibre Ebook Management</a> - it's free and easy to use. You can't go wrong.</li>
<li><a href="https://sigil-ebook.com/">Sigil Ebook Editor</a> - also free and easy to use.</li>
</ul>
