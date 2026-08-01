---
layout: default
title: "Comics"
permalink: /comic/
---

<h1>Comics</h1>

<p>Browse the current comic episodes below.</p>

<ul class="comic-list">
  {% assign comics = site.comics | sort: "comic_order" %}
  {% for comic in comics %}
    <li>
      <a href="{{ comic.url }}">
        {% if comic.thumb %}
          <img src="{{ comic.thumb }}" alt="{{ comic.title }}" />
        {% elsif comic.image %}
          <img src="{{ comic.image }}" alt="{{ comic.title }}" />
        {% endif %}
        <h2>{{ comic.title }}</h2>
      </a>
    </li>
  {% endfor %}
</ul>
