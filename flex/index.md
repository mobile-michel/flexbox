---
title: Flex Properties
description: This is the blog.
override:tags: [primary]
pagination:
    data: collections.flex
    size: 3
    alias: pagination
---
{%- for item in pagination %}
- <a href="{{ item.url | url }}">{{ item.data.description }}</a>
{% endfor -%}
