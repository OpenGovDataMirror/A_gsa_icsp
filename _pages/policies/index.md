---
title: Policies
permalink: /policies/
layout: page
section: policies
---
{% assign pages = site.pages | where: "section", "policies" %}
{% for page in pages %}
{% unless page.permalink %}{% unless page.skip %}
<h3 class="bg-primary text-white radius-lg padding-1 font-sans-xs">{{ page.title }}</h3>
{{ page.content | render }}
{% endunless %}{% endunless %}
{% endfor %}