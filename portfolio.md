---
layout: page
title: Portfolio
url: /portfolio
---

Below is a selection of projects I'd like to expand upon from [my resume]({{ '/assets/portfolio/asacosta_resume.pdf' | relative_url }}), including ones that are no longer there for relevance reasons.

As of late July 2026, this page is still in its infancy and is not representative of my full portfolio. There are other things I'd like to add, and each individual card needs to be fully fleshed out.

<div class="layout--articles">
  <section class="my-5">
    <header><h2 id="page-layout">Academic and Professional</h2></header>
    <hr>
    {%- include article-list.html articles=site.projects type='grid' -%}
  </section>

  <section class="my-5">
    <header><h2 id="articles-layout">Personal</h2></header>
    <p>Several of these won't have my absolute "peak" performance in them because those weren't recorded, but it will hopefully successfully sample my level of practice.</p>
    <hr>
    {%- include article-list.html articles=site.hobbies type='grid' -%}
  </section>
</div>

