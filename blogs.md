---
layout: base
title: Blogs
permalink: /blogs/
---

{%- if site.blogs.size > 0 -%}
<ul class="post-list">
    {%- assign reversed_blogs = site.blogs | reverse -%}
    {%- for post in reversed_blogs -%}
    <li>
<!--    {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
    <span class="post-meta">{{ post.date | date: date_format }}</span> --> 
    <h3>
        <a class="post-link" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
        </a>
    </h3>
    {%- if site.show_excerpts -%}
        {{ post.excerpt }}
    {%- endif -%}
    </li>
    {%- endfor -%}
</ul>
{%- endif -%}