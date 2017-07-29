---
---

{% for post in site.posts %}
{% include post/brief.html %}
{% unless forloop.last %}<hr>{% endunless %}
{% endfor %}
