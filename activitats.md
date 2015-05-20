---
layout: page
title: "Activitats d'<span class='light'>#Espai</span>Sid"
category: mur-diari
---

<div class="posts clearfix">
  {% for post in site.categories['exposicionssid'] limit:4 %}
  <div class="post">
  <h2><span class='light'>#Exposicions</span>SID</h2>
    {{ post.excerpt }}    

  <h2 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    <p class="text-center"><a href="{{ post.url }}"><i class="fa fa-lg fa-plus-square-o"></i></a></p>
    </div>
  {% endfor %}
  {% for post in site.categories['capsulessid'] limit:4 %}
  <div class="post">
  <h2><span class='light'>#Càpsules</span>SID</h2>

    {{ post.excerpt }}    

  <h2 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    <p class="text-center"><a href="{{ post.url }}"><i class="fa fa-lg fa-plus-square-o"></i></a></p>
    </div>
  {% endfor %}
</div>