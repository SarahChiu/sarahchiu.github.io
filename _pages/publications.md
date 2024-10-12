---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<div class="wordwrap">* indicates equal contribution. You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>

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
