---
layouts: page
title: About
permalink: index.html
---

<div>
{{ "## Yes, this renders as markdown" | markdownify }}
</div>

<ul>
  {% for page in site.article %}
    <li>
      <a href="{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>

