---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<h1>Poems</h1>

<p>{% for poem in site.poems %}
    <a href="{{ poem.url }}">
      {{ poem.title }}
    </a>
    
{% endfor %}</p>