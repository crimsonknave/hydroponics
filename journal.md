---
navbar: true
---
<ul>
    {% for page in site.pages %}
      {% if page.navbar == "true" %}
        <li><a href="{{ doc.url }}">{{ doc.title }}</a></li>
      {% endif %}
    {% endfor %}
</ul>

# Journal

I keep a journal where I note down what's going on with the plants. When I change/add water, what's healthy, what's not. 
I'll be transcribing my journal here and also adding in notes based on what I've learned since I wrote it.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/hydroponics/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
