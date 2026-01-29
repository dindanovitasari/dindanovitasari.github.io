---
layout: cv
title: CV
permalink: /cv/
nav: true
nav_order: 2
---

# Dinda Novitasari

Machine Learning Engineer | East Java, Indonesia

---

## Professional Summary

Applied machine learning practitioner with 6+ years of experience building and deploying ML models in industry. Specialized in natural language processing, information retrieval, and recommender systems. Proven track record of productionizing models, designing scalable data pipelines, and delivering measurable business impact.

---

## Experience

### Telkomsel — Data Scientist (2023–Present)

**Digital Prodigy Team**
- Lead productionization of 20+ ML models across multiple business use cases targeting millions of users monthly
- Improved ML pipeline efficiency, reducing processing time from days to hours
- Built propensity and segmentation models driving ARPU uplift and revenue growth
- Developed automated data pipelines for campaign tracking and monitoring
- Advised stakeholders and business units on ML implementation strategies
- Collaborate with external consultant teams to deploy scalable solutions

### Telkomsel — Machine Learning Engineer (2020–2023)

**Digital Prodigy Team**
- Designed and productionized ML models and data pipelines
- Improved existing machine learning pipeline efficiency
- Improved report availability through dashboard automation
- Built propensity models driving business impact
- Performed customer value analysis and segmentation for marketing initiatives
- Built automated campaign tracking data pipelines for monitoring

### A Job Thing — Machine Learning Engineer (2018–2020)

- Built content-based recommender systems using Doc2Vec and TF-IDF, achieving 30% improvement in recommendation relevancy
- Designed and implemented data pipelines from MySQL to Elasticsearch using Logstash, handling 100K+ daily events
- Developed personalized recommendation engine using hybrid algorithms combining collaborative and content-based filtering
- Optimized search relevancy and query performance on Elasticsearch indexes with 1M+ documents
- Built analytics dashboards with Dash for real-time monitoring of system performance
- Implemented multi-language tag recommender using POS-tag based linguistic features

---

## Technical Skills

**Machine Learning & Data Science**
- Statistical analysis, supervised/unsupervised learning, classification, clustering, anomaly detection
- Model evaluation, hyperparameter optimization, cross-validation, feature engineering

**Programming Languages**
- Python (primary language: pandas, scikit-learn, TensorFlow, Keras)
- MATLAB, SQL, basic Java

**Data Engineering**
- Web scraping, ETL pipeline design, data warehousing
- SQL/NoSQL: MySQL, Firebase, Hive
- Big data: Hadoop, Spark (Scala, PySpark)

**Tools & Libraries**
- ML: Pandas, scikit-learn, NLTK, spaCy, Gensim, XGBoost
- Search & Indexing: Elasticsearch, Logstash, Kibana
- Web Frameworks: Flask, Django basics
- Task Queue: Celery, Redis
- Orchestration: Kedro

**Cloud & Infrastructure**
- AWS EC2, basic deployment and scaling
- Docker fundamentals

---

## Education

### National Central University, Taiwan
**M.S. Computer Science and Information Engineering** (2016–2018)
- GPA: 3.88/4.00
- Thesis: "The Role of Comprehensive Income and Accrual in Predicting Bankruptcy"
- Advisor: Prof. Deron Liang
- Focus: Machine learning, data mining, statistical methods

### Brawijaya University, Indonesia
**B.S. Informatics** (2011–2015)
- GPA: 3.56/4.00
- Thesis: "Optimization of Support Vector Regression with Particle Swarm Optimization for Software Effort Estimation"
- Focus: Software engineering, optimization algorithms, predictive modeling

---

## Certifications

- **IBM Certified Database Associate** – DB2 9 Fundamentals (2014)
- **IBM Certified Solution Designer** – Object Oriented Analysis and Design, vUML 2 (2014)
- **IC3 Digital Literacy Certification** (2012)

---

## Publications

{% for p in site.data.publications.journals %}
- {{ p.authors }}. "{{ p.title }}". *{{ p.journal }}*, {{ p.year }}. [Link]({{ p.link }})
{% endfor %}

---

## Languages

- **Indonesian** (Native)
- **English** (Fluent)
- **Mandarin Chinese** (Basic)

---

## Interests

Machine learning systems design, open-source contribution, technical writing, hiking, reading about emerging AI/ML trends.

---

*Last updated: January 2026*
