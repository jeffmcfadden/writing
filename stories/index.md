---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<h1>Stories</h1>

<p class="text-center">
  {% for story in site.data.stories %}
    <a href="{{ story.url }}">{{ story.title }}</a><br />
  {% endfor %}
</p>