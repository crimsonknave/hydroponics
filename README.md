---
title: Main Page
navbar: true
---
<ul class="navbar">
    {% for page in site.pages %}
      {% if page.navbar == true %}
        <li class="navbar-page"><a href="{{ page.url }}">{{ page.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>
# Main Page
Here's where I'll have generic stuff and an intro
