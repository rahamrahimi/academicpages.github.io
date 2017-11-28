---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Rahimi, Reza, and Runar Nygaard. "Comparison of rock failure criteria in predicting borehole shear failure." International Journal of Rock Mechanics and Mining Sciences 79 (2015): 29-40.](http://www.sciencedirect.com/science/article/pii/S136516091530006X)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
