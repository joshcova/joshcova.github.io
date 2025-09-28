---
layout: archive
title: "Data"
permalink: /data/
author_profile: true
---
**[*ItaParlCorpus*](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/KUARWD) (Cova, 2025)**

ItaParlCorpus is a **machine-readable** and **annotated** corpus of parliamentary speeches from Italy's lower chamber of Parliament, the *Camera dei Deputati*. 

This comprehensive corpus contains all parliamentary speeches from the Italian post-war republican period (1948-2022) and is the first fully annotated corpus that links parliamentary interventions to specific parliamentary groups across the country's entire republican history. 

Covering 18 legislatures, 68 different governments, the corpus includes over 470 million words, 2.4 million speeches, from 6,263 unique speakers representing 154 different political parties. 

**[*CommonsCorpus*](https://dataverse.harvard.edu/dataverse/CommonsCorpus) (Cova and Germani, 2025)**

CommonsCorpus is a **machine-readable** and **annotated** corpus of parliamentary speeches from the UK House of Commons (1970-2024). Parliamentary speech data is integrated with metadata on speakers' socio-demographic information and party-poltiical affiliation and is available as .csv files.

To extend the time series of the corpus, prospective users are invited to consult the following [**GitHub Repository**](https://github.com/joshcova/CommonsCorpus)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
