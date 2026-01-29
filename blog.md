---
layout: page
title: Blog
permalink: /blog/
nav: true
nav_order: 4
---

## Latest Posts

<div class="posts-list">
  {% for post in site.posts %}
    <div class="post-preview">
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <p class="post-meta">
        <time datetime="{{ post.date | date_to_xmlschema }}" itemprop="datePublished">
          {{ post.date | date: "%B %d, %Y" }}
        </time>
      </p>
      {% if post.description %}
        <p class="post-excerpt">{{ post.description }}</p>
      {% elsif post.content %}
        <p class="post-excerpt">{{ post.content | strip_html | truncatewords: 30 }}</p>
      {% endif %}
      <a href="{{ post.url | relative_url }}" class="read-more">Read more →</a>
    </div>
    <hr>
  {% endfor %}
</div>

<style>
  .posts-list {
    max-width: 100%;
  }

  .post-preview {
    margin-bottom: 30px;
    padding-bottom: 20px;
  }

  .post-preview h3 {
    margin-top: 0;
    margin-bottom: 10px;
  }

  .post-preview h3 a {
    color: #0066cc;
    text-decoration: none;
  }

  .post-preview h3 a:hover {
    text-decoration: underline;
  }

  .post-meta {
    font-size: 0.9em;
    color: #666;
    margin: 5px 0;
  }

  .post-excerpt {
    color: #555;
    line-height: 1.6;
    margin: 10px 0;
  }

  .read-more {
    color: #0066cc;
    text-decoration: none;
    font-weight: 500;
  }

  .read-more:hover {
    text-decoration: underline;
  }

  hr {
    border: none;
    border-top: 1px solid #eee;
    margin: 20px 0;
  }
</style>
