---
layout: default
---


# Knowledge in Learning Patterns

<ul>
{% for post in site.posts %}
  <li>
      <a href="{{ post.url | relative_url }}">
        {{ post.title }}
      </a>
    <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
  </li>
{% endfor %}
</ul>


# All Pages

<ul>
{% for page in site.pages %}
  <li>
    <a href="{{ page.url | relative_url }}">
      {{ page.name }}
    </a>
    <time datetime="{{ page.date }}">{{ page.date }}</time>
  </li>
{% endfor %}
</ul>
