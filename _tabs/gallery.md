---
order: 4
images: /assets/instagram/
---
<hr>
## _#mylastour_  on [instagram](https://www.instagram.com/narayanagung/)

{% assign images = site.static_files %}
{% for image in images %}
{% if image.path contains '/assets/instagram/' %}
<p>{{ image.basename }}</p>
<img src="{{ image.path }}" alt="preview images for my ig">
{% endif %}
{% endfor %}
_Selengkapnya bisa dilihat [disini](https://www.instagram.com/narayanagung/)_
