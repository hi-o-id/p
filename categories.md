---
layout: page
title: 分类归档
permalink: /categories/
---

<div class="categories-index">
  <h1 class="page-heading">📂 按分类浏览</h1>

  {% assign categories = site.categories | sort %}
  
  {% for category in categories %}
    {% assign category_name = category[0] %}
    {% assign category_posts = category[1] %}
    
    <section class="category-section" id="{{ category_name | slugify }}">
      <h2 class="category-title">
        <a href="{{ '/category/' | append: category_name | slugify | relative_url }}">
          {% if category_name == "Apple" %}
            🍎
          {% else %}
            📋
          {% endif %}
          {{ category_name }}
        </a>
        <span class="post-count">({{ category_posts | size }} 篇)</span>
      </h2>
      
      <ul class="post-list">
        {% for post in category_posts limit: 5 %}
          <li>
            <span class="post-meta">{{ post.date | date: "%Y-%m-%d" }}</span>
            <h3>
              <a class="post-link" href="{{ post.url | relative_url }}">
                {{ post.title | escape }}
              </a>
            </h3>
          </li>
        {% endfor %}
      </ul>
      
      {% if category_posts.size > 5 %}
        <p class="view-more">
          <a href="{{ '/category/' | append: category_name | slugify | relative_url }}">
            查看全部 {{ category_posts.size }} 篇文章 →
          </a>
        </p>
      {% endif %}
    </section>
  {% endfor %}
</div>

<style>
  .categories-index {
    max-width: 800px;
  }
  
  .category-section {
    margin-bottom: 2rem;
    padding: 1.5rem;
    background: #f8f9fa;
    border-radius: 8px;
    border-left: 4px solid #007bff;
  }
  
  .category-section:nth-child(even) {
    border-left-color: #28a745;
  }
  
  .category-title {
    margin-top: 0;
    margin-bottom: 1rem;
    border-bottom: 2px solid #dee2e6;
    padding-bottom: 0.5rem;
  }
  
  .category-title a {
    text-decoration: none;
    color: #495057;
  }
  
  .category-title a:hover {
    color: #007bff;
  }
  
  .post-count {
    font-size: 0.8em;
    color: #6c757d;
    font-weight: normal;
    margin-left: 0.5rem;
  }
  
  .view-more {
    margin-top: 1rem;
    text-align: right;
  }
  
  .view-more a {
    color: #007bff;
    text-decoration: none;
  }
  
  .view-more a:hover {
    text-decoration: underline;
  }
</style>
