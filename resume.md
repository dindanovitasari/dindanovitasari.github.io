---
layout: default
title: Resume
permalink: /resume/
---

<style>
/* Print rules scoped to resume page: hide navigation and page chrome and optimize PDF output */
@page { margin: 1.2cm; }
@media print {
	body * { visibility: hidden; }
	#longbio, #longbio * { visibility: visible; }
	#longbio { position: absolute; left: 0; top: 0; width: 100%; font-size: 12pt; }
	h1, h2, h3 { page-break-after: avoid; page-break-inside: avoid; }
	.page-break { page-break-before: always; }
}
</style>

<div id="longbio">

# Dinda Novitasari

<img src="/images/profile.png" alt="Photo of Dinda" style="float:right;width:150px;border-radius:50%;margin-left:1rem;">

**Email:** id[dot][firstname lastname][at]gmail[dot]com  
**Location:** East Java, Indonesia

## Professional Summary

An applied machine learning practitioner with experience building and deploying models in industry. Research interests include natural language processing, information retrieval, and recommender systems. Skilled in model productionization, data pipelines, and evaluation.

## Experiences

### Telkomsel — Machine Learning Engineer (2020–Present)

Part of Digital Prodigy Team. Responsibilities include building and productionizing ML models and pipelines.

### A Job Thing — Machine Learning Engineer (2018–2020)

- Built content-based recommender systems using Doc2Vec and TF-IDF
- Built data pipelines and warehousing for content and user data using Elasticsearch
- Developed personalised recommendation engines using hybrid algorithms
- Optimised search relevancy and performance using Elasticsearch
- Built data pipelines from MySQL → Elasticsearch with Logstash
- Built analytics dashboards with Dash
- Multi-language tag recommender using POS-tag based approaches

## Skills

- Machine Learning, Statistical Analysis, Data Mining, Classification, Clustering
- Programming: Matlab, Python
- Data Engineering: Web scraping, SQL, NoSQL, ETL
- Soft skills: Project management

## Tools

- Cloud: AWS EC2
- Databases: MySQL, Firebase, Hive
- Libraries: Hadoop, Spark, Kedro, Pandas, scikit-learn, NLTK, spaCy, Gensim, Elasticsearch, Logstash, Flask, Redis, Celery, xgboost

## Certifications

- IBM Certified Database Associate DB2 9 Fundamentals
- IBM Certified Solution Designer – Object Oriented Analysis and Design, vUML 2
- IC3 Digital Literacy Certification

## Education

### National Central University — MS, Computer Science and Information Engineering (2016–2018)

GPA: 3.88/4.00  
Supervised by: Prof. Deron Liang

### Brawijaya University — BS, Informatics (2011–2015)

GPA: 3.56/4.00

## Published Works

## Research

My work spans both applied industry projects and academic research. I focus on building robust, scalable ML systems and improving retrieval and recommendation quality using hybrid approaches.

## Selected publications

{% for p in site.data.publications.journals %}
- **{{ p.authors }}**. "{{ p.title }}" — _{{ p.journal }}_, {{ p.year }}. {% if p.link %}[pdf]({{ p.link }}){% endif %}
{% endfor %}

## Theses

{% for t in site.data.publications.theses %}
- **{{ t.type }}:** {{ t.title }} {% if t.link %}[link]({{ t.link }}){% endif %}
{% endfor %}

</div>
