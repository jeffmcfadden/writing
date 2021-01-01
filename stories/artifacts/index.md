---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<h1>4 Artifacts</h1>

<h3>Table of Contents</h3>
<p>{% for chapter in site.artifacts_chapters %}
    <a href="{{ chapter.url }}">
      Chapter {{ chapter.ordinal }} — {{ chapter.title }}
    </a>
    
{% endfor %}</p>