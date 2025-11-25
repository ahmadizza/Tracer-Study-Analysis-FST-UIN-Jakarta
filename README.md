## **Project Overview**

This project analyzes alumni data from the Faculty of Science and Technology (FST), UIN Syarif Hidayatullah Jakarta. The dataset contains 435 entries and provides insights into academic background, employment outcomes, income distribution, career paths, entrepreneurship involvement, and the relevance of academic programs to professional trajectories. The study aims to identify trends, evaluate curriculum effectiveness, and support strategic planning for improving alumni career readiness.

## **Data Understanding**

The dataset includes multiple variables describing alumni characteristics and outcomes, such as:

* Entry and graduation year
* Employment timing
* Current job status
* Entrepreneurship activities
* Company and job position
* Monthly income
* Further education details
* Curriculum and field relevance
* Suggestions for program improvement
* Undergraduate program
* Missing or unused fields removed during preprocessing

### Preprocessing Steps

* Removal of irrelevant columns: phone number, email, timestamp
* Removal of fully empty columns
* Conversion of data types to appropriate formats
* Handling duplicates and noise
* Outlier retention because income variation reflects real job market differences
* Missing value imputation with "none" for categorical consistency

## **Exploratory Data Analysis (EDA)**

The analysis explores several aspects, including:

### Alumni Submission Trend

Submission peaked in June 2024 and declined afterward. The faculty is recommended to send periodic reminders to improve participation.

### Study Duration vs. Income

No clear correlation is found between study duration and income. Employment timing also does not strongly affect income differences.

### Income vs. Employment Timing by Current Status

* Most alumni gain employment within three months.
* Higher income appears among ASN/PNS and private employees.
* Freelancers and job seekers earn less on average.
  Recommendations include strengthening skills training, industry partnerships, and career support.

### Program Study vs. Income and Job Relevance

* MAG and Physics alumni show higher income when working in aligned fields.
* Mathematics and Biology alumni earn high incomes even outside their field.
* Informatics and Mining Engineering display varied patterns influenced by experience or location.

### Job Status Distribution by Program Study

Most private employees come from Informatics, Mathematics, and Biology.
Most educators are Biology graduates.
Entrepreneurs appear across multiple programs.

### Undergraduate and Postgraduate Program Relationship

Mathematics and Agribusiness alumni tend to continue in related programs.
Physics graduates pursue diverse fields in graduate studies.

### Entrepreneurship Analysis

A breakdown of entrepreneurship patterns across programs shows that Biology and Mathematics have the highest entrepreneurial engagement.

### Word Cloud Insights

Frequent job positions include Staff and Engineer, with many alumni working in PT companies or technology-related roles.

## **Association Rules (Market Basket Analysis)**

The model evaluates the relationship between undergraduate program and job status.

Key findings:

* Informatics alumni have the strongest tendency to become private employees (confidence 87.7%, lift 1.29).
* Mathematics alumni also show high likelihood (confidence 78.1%, lift 1.15).
* Biology, Physics, and Chemistry have weaker associations.

Recommendations include enhancing career pathways for science-based programs through curriculum alignment and industry collaboration.

## **Clustering (K-Prototypes)**

Clustering identifies groups of alumni with similar employment patterns, income levels, study duration, and background.

Cluster insights include:

* High-income clusters dominated by Informatics and Mathematics alumni
* Entrepreneurship-heavy clusters
* Diverse clusters with various employment timings and study backgrounds

These clusters support segmentation strategies for improving career services and curriculum development.

---
