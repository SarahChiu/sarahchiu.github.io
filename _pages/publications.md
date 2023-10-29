---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.preprint == 'N' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

---

# Preprint and Under Submission

{% for post in site.publications reversed %}
  {% if post.preprint == 'Y' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
