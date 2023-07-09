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
  {% include archive-single.html %}
{% endfor %}

## Other theoretical work

- Yangjun Yan, **Shengda Zhao**, Yajie Zhang, *et al*. Molecular Orientation Dependent Exciton Separation in Optimized Single Component Y6 Organic Solar Cells. Solar RRL, 2023. [DOI:10.1002/solr.202300342.]{https://doi.org/10.1002/solr.202300342}