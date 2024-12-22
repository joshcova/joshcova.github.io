---
layout: archive
title: "Data"
permalink: /data/
author_profile: true
---
**ItaParlCorpus (Cova, 2024)**

ItaParlCorpus is a **machine-readable** and **annotated** corpus of parliamentary speeches from Italy's lower chamber of Parliament, the *Camera dei Deputati*. 

This comprehensive corpus contains all parliamentary speeches from the Italian post-war republican period (1948-2022) and is the first fully annotated corpus that links parliamentary interventions to specific parliamentary groups across the country's entire republican history. 

Covering 18 legislatures, 68 different governments, the corpus includes over 470 million words, 2.4 million speeches, from 6,263 unique speakers representing 154 different political parties. 

[*Harvard Dataverse*](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/KUARWD)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
