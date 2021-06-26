---
title: Seedlings
navbar: true
---
<ul class="navbar">
    {% for page in site.pages %}
      {% if page.navbar == true %}
        <li class="navbar-page"><a href="{{ page.url }}">{{ page.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>
# Seedlings
Here I'll document how I've grown things from seed
