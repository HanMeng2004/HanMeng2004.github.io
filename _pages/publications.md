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
[here](/files/pdf/2024_arxiv_Exploring_the_Potential_of_Human_LLM_Synergy_in_Advancing_Qualitative_Analysis.pdf)
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
