---
layout: page
title: Notes
---

<ul>
  {% for note in collections.posts.notes %}
    <li>
      <a href="{{ note.relative_url }}">{{ note.data.title }}</a>
    </li>
  {% endfor %}
</ul>

<article>
  <p>Across stacks, platforms, and domains (e.g., eCommerce, fintech, healthcare, etc.), the engineering team can take on two software development types: greenfield and brownfield development. Each development type brings specific opportunities and challenges that require adapting various components and best practices of the development processes.</p>

  <h2>Greenfield</h2>

  <h3>Characteristics</h3>

  <p>Greenfield development involves creating a system for a business domain and use case without existing code, i.e., starting from scratch. Beyond requiring a specific stack, the novel software might still have constraints, such as using specific dependencies (e.g., third-party services, libraries, etc.). However, the squad works on a clean slate where every part of the system must be defined and implemented.</p>

  <p>Greenfield development usually occurs when a new business venture is set up, thus needs new software, or when an existing business opts to reimplement a new version of its existing software.</p>

  <h3>Opportunities</h3>

  <p>Working on a greenfield codebase brings the following advantages:</p>

  <ul>
    <li>Implementing the latest development patterns and best practices for the stack that the application is built on. The new codebase can leverage the latest proven patterns and tools.</li>
    <li>Developing the codebase using all the team’s development and code conventions, including [version control](/development/version-control/), [testing](/development/testing/), [localization](/development/localization/), and [documentation](/development/documentation/). As a result, the codebase can represent the best of what the engineering team can produce.</li>
    <li>Unencumbered and predictable development thanks to the total ownership of every part of the codebase. The team possesses an in-depth understanding of every aspect of the code, thus can guarantee the application fulfills all acceptance criteria and can more easily debug any issue that might occur.</li>
  </ul>

  <pre>
    module.exports = {
      purge: [],
      theme: {
        extend: {},
      },
      variants: {},
      plugins: [],
    }
  </pre>
</article>