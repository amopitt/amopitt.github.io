---
layout: default
active: home
---

<section class="intro  section--pad">
  <h1>Hi, I'm Mark Goodyear.</h1>
</section>

<section class="posts  section--pad">
  <h2 class="section-title">Latest Posts</h2>

  {% include post-list.html limit=6 collection=site.posts %}

  <a href="/blog" class="btn">View all posts &rarr;</a>
</section>

 