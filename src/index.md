---
layout: default
page_class: home
---

<div class="callout-block">
  <p>Hi 👋 I am Olivier.</p>
  <p>Here I write about what I learn and find useful in my day-to-day life as a human, software crafter, and engineering leader.</p>
</div>

<section class="featured-content">
  <header class="featured-content__header">
    <h2 class="featured-content__heading">Latest Articles</h2>
    <a href="/articles" class="featured-content__action link--backgroundless">View all</a>
    <p class="featured-content__subheading">Long-form-writing on software engineering, engineering management, and personal productivity.</p>
  </header>

  {% render "list_resource", resources: collections.posts.resources, class_name: "featured-content__list" %}
</section>

<section class="featured-content">
  <header class="featured-content__header">
    <h2 class="featured-content__heading">Latest Notes</h2>
    <a href="/notes" class="featured-content__action link--backgroundless">View all</a>
    <p class="featured-content__subheading"> Short-form-writing on my current interests and learnings. A mix between a TIL knowledge base and a Zettelkasten.</p>
  </header>

  {% render "list_resource", resources: collections.notes.resources class_name: "featured-content__list" %}
</section>
