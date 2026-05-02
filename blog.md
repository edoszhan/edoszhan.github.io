---
layout: page
title: Blog
description: "Writing on machine learning papers, tools, and software engineering."
---

<div class="blog-header">
  <h1>Blog</h1>
  <p>Notes on papers I've read, tools I use, and things I'm learning.</p>
</div>

<div class="blog-filters">
  <button class="blog-filter active" data-filter="all">All</button>
  <button class="blog-filter" data-filter="papers">Papers</button>
  <button class="blog-filter" data-filter="long-form">Long Form</button>
  <button class="blog-filter" data-filter="tools">Tools</button>
  <button class="blog-filter" data-filter="notes">Notes</button>
</div>

<div class="blog-entry-list">
  {% for post in site.posts %}
  {% assign post_cat = post.categories | first | downcase | replace: ' ', '-' %}
  <div class="blog-entry" data-category="{{ post_cat }}">
    <time class="blog-entry-date">{{ post.date | date: "%B %-d, %Y" }}</time>
    <h3 class="blog-entry-title">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </h3>
    {% if post.description %}
      <p class="blog-entry-desc">{{ post.description }}</p>
    {% endif %}
  </div>
  {% endfor %}
</div>

<script>
  (function () {
    var filters = document.querySelectorAll('.blog-filter');
    var entries = document.querySelectorAll('.blog-entry');
    filters.forEach(function (btn) {
      btn.addEventListener('click', function () {
        filters.forEach(function (b) { b.classList.remove('active'); });
        btn.classList.add('active');
        var f = btn.dataset.filter;
        entries.forEach(function (entry) {
          entry.style.display = (f === 'all' || entry.dataset.category === f) ? '' : 'none';
        });
      });
    });
  })();
</script>
