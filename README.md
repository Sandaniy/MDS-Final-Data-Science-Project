# MDS-Final-Data-Science-Project
This repository contains the python notebooks that accompany the Final Project Report.

As legal systems contend with increasing caseloads and evolving complexities in different areas of law, the need for data-driven insights to understand and enhance judicial decision-making becomes more pronounced. This study utilises natural language processing (NLP) and machine learning algorithms to first, examine appellate judicial decision-making in the United Kingdom, and second, classify United Kingdom Supreme Court (UKSC) judgments into specific areas of law. The primary data are the 2009-2023 judgments of the United Kingdom Supreme Court (UKSC) which were mined using web-scraping. Regular expressions (regex) were used to extract information from judgments (e.g. citations, appealed case, dates of judgments and hearings, names of judges), and judgments were manually labelled to reflect which area of law it primarily falls into (e.g. human rights, immigration, criminal etc). The analysis is of two primary parts. First, questions relating to laws delays (e.g. duration taken to conclude cases), judicial workload (e.g. no. of judgments delivered, and when), devolution (e.g. numbers of cases appealed to the UKSC from England and Wales, Scotland, Northern Ireland), nature of cases allowed or dismissed etc. are examined. Second, several machine learning algorithms (e.g. Naïve Bayes, KNN, Ensemble methods, neural networks) are deployed using the labelled dataset to build classifiers to classify judgments into legal areas, and its performance evaluated. In closing, the Report engages with the findings and its implications for resource allocation within the UKSC and legal research, the challenges of working with legal text data, and possible future research directions.
