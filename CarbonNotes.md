---
layout: page
title: Carbon Notes
permalink: /carbonnotes
---

A module-by-module guide to Whole Life Carbon Assessment (WLCA) — lessons learned and practical tips from RICS WLCA training and real-world practice.

<ul class="post-list">
{%- assign carbon_notes = site.categories['carbon-notes'] | sort: 'date' -%}
{%- for post in carbon_notes -%}
  <li>
    <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    <h3>
      <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
    </h3>
  </li>
{%- endfor -%}
</ul>
