---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Please find below a list of my publications: 

Peer-reviewed publications
==========

**Cova, Joshua (2022)**, 'Reconsidering the drivers of country-specific recommendations: The Commission's ideological preferences on wage policies' [*European Union Politics*](https://journals.sagepub.com/doi/full/10.1177/14651165221102696), 23(4), pp.639-661

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
