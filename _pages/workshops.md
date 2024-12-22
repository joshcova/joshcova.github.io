---
layout: archive
title: "Workshops"
permalink: /workshops/
author_profile: true
---
Please find below a list of workshops I have run: 

**Large language models in social science research** (with [Luuk Schmitz](https://luukschmitz.com/))

* Online workshop series designed for advanced graduate students focusing on how to interact with classifiers and LLMs 
* [Slides](https://github.com/joshcova/LLMs-for-social-scientists)
* Paper: **Cova, Joshua and Schmitz, Luuk (2024)**, 'A primer for the use of classifier and generative large language models in social science research', [*OSF Preprints*](https://osf.io/preprints/osf/r3qng)

**Introduction to Python**

* Workshop offered to PhD students at the Max Planck Institute 
* [Slides](https://github.com/joshcova/Intro-to-Python)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
