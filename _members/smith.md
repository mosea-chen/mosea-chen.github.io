---
---
# hello world
{% assign image_files = site.static_files %}
{% for myimage in image_files %}
  {{ myimage.path }}
  {{ myimage.name}}
{% endfor %}