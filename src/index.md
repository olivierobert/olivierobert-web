---
layout: default
page_class: home
---

<h2>A software engineer at heart and a hands-on engineering leader by trade.</h2>

Hi, I am Olivier 👋 I enjoy building and working with high-performing engineering and product teams. I am currently leading the engineering team at [Nimble](https://nimblehq.co/).

<section class="content-section">
  <header>
    <h2>Latest Articles</h2>
    <small><a href="/articles">View all</a></small>
  </header>

  Long-form-writing on software engineering, engineering management, and personal productivity.

  {% render "list_latest_resource", resources: collections.posts.resources %}
</section>

<section class="content-section">
  <header>
    <h2>Latest Notes</h2>
    <small><a href="/notes">View all</a></small>
  </header>

  Short-form-writing on my current interests and learnings. A mix between a TIL knowledge base and a Zettelkasten.

  {% render "list_latest_resource", resources: collections.notes.resources %}
</section>
