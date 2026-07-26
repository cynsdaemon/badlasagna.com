---
layout: default
title: "Bad Lasagna"
permalink: /
---

# Welcome to Bad Lasagna Comic    

Bad Lasagna is a cozy, weird comic about cosmic bureaucracy, emotional labor, and the daemons who run it. 
This project is my playground for cozy-weird storytelling and maintaining a sustainable creative practice.
Thanks for reading and being part of my experiment.

## Start Reading

{% assign pages = site.comics | sort: "order" %}
{% if pages.size > 0 %}
[Read the Latest Comic →]({{ pages.last.url }})
{% endif %}

## Browse the Archive

[Comic Archive →](/archive/)

## Blog

[Updates & Behind the Scenes →](/blog/)
