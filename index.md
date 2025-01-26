---
layout: default
---

<div class="header-bar">
  <h1>Meishan Fan</h1>
  <h2>
    <!-- <a href="https://4-h.org/about/luminaries/#!our-luminaries" target="_blank">4-H</a>, -->
    <!-- <a href="/projects/music" target="_blank">music</a> -->
  </h2>
</div>
{%- comment -%}
<hr>
<ul class="post-list">
    {%- for post in paginator.posts -%}
      <li>
        <h2><a class="post-title" href="{{- post.url | prepend: site.baseurl -}}">{{- post.title -}}</a></h2>
        <p class="post-meta">{{- post.date | date: '%B %-d, %Y — %H:%M' -}}</p>
        <p>{{- post.description -}}</p>
        <br/>
        <hr/>
      </li>
    {%- endfor -%}
</ul>
{%- endcomment -%}
