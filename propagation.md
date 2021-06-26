---
title: Propagation
navbar: true
---
<ul class="navbar">
    {% for page in site.pages %}
      {% if page.navbar == true %}
        <li class="navbar-page"><a href="{{site.baseurl}}{{ page.url }}">{{ page.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>
# Propagation
Here I'll document my successes and failures to propagate cuttings.
