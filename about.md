---
layout: page
title: About
permalink: /about/
---

# Dinda Novitasari

An applied machine learning practitioner with experience building and deploying models in industry. Research interests include natural language processing, information retrieval, and recommender systems. Skilled in model productionization, data pipelines, and evaluation.

Contact: id[dot][firstname lastname][at]gmail[dot]com

## Education

- National Central University — MS, Computer Science and Information Engineering (2016–2018)
- Brawijaya University — BS, Informatics (2011–2015)

## Selected publications

{% for p in site.data.publications.journals %}
- **{{ p.authors }}**. "{{ p.title }}" — _{{ p.journal }}_, {{ p.year }}. {% if p.link %}[pdf]({{ p.link }}){% endif %}
{% endfor %}
