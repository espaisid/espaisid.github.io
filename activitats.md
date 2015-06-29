---
layout: page
title: "Activitats d'<span class='light'>#Espai</span>Sid"
category: mur-diari
---


<div class="posts clearfix">
  <h2><span class='light'>#Càpsules</span>SID</h2>
  {% for post in site.categories['capsulessid'] limit:4 %}
  <div class="post">

    {{ post.excerpt }}   

    <br/> 

  <h2 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    <p class="text-center"><a href="{{ post.url }}"><i class="fa fa-lg fa-plus-square-o"></i></a></p>
    </div>
  {% endfor %}
</div>
<div class="posts clearfix">
  <h2><span class='light'>#Exposicions</span>SID</h2>
  {% for post in site.categories['exposicionssid'] limit:4 %}
  <div class="post">
    {{ post.excerpt }} 

    <br/>   

  <h2 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    <p class="text-center"><a href="{{ post.url }}"><i class="fa fa-lg fa-plus-square-o"></i></a></p>
    </div>
  {% endfor %}
</div>
<div class="posts clearfix">
  <h2><span class='light'>#Notícies</span>SID</h2>
  {% for post in site.categories['noticiessid'] limit:4 %}
  <div class="post">

    {{ post.excerpt }}

    <br/>    

  <h2 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    <p class="text-center"><a href="{{ post.url }}"><i class="fa fa-lg fa-plus-square-o"></i></a></p>
    </div>
  {% endfor %}
</div>