---
layout: default
title: "Comics"
permalink: /comic/
---

<div class="comic-landing-page">
  <div class="comic-landing-header">
    <h1>Comics</h1>
    <p>Browse the current comic episodes below.</p>
  </div>

  <div class="comic-card-grid">
    {% assign comics = site.comics | sort: "comic_order" %}
    {% for comic in comics %}
      <article class="comic-card">
        <a href="{{ comic.url }}" class="comic-card-link">
          <div class="comic-card-thumb">
            {% if comic.thumb %}
              <img src="{{ comic.thumb }}" alt="{{ comic.title }}" />
            {% elsif comic.image %}
              <img src="{{ comic.image }}" alt="{{ comic.title }}" />
            {% else %}
              <div class="bl-monogram">{{ comic.title | slice: 0, 1 }}</div>
            {% endif %}
          </div>
          <div class="comic-card-content">
            <p class="comic-card-number">Episode {{ comic.comic_order | default: 1 }}</p>
            <h2>{{ comic.title }}</h2>
          </div>
        </a>
      </article>
    {% endfor %}
  </div>
</div>
