---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<iframe src="https://scholar.google.com/citations?user=QJqgMoEAAAAJ&hl=en&oi=ao"></iframe>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
