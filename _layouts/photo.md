---
layout: photo
---
<div class="photo">

  <header class="photo-header">
    <h1 class="post-title">{{ page.title }} by {{ page.byline }}</h1>
  </header>

  <article class="post-content">
    <img src="{{ page.photo_url }}" alt="{{ page.title }}">
    {{ content }}
  </article>

</div>
