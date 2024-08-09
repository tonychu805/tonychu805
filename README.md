# Tony Chu - Data Analysis Portfolio 

## I. About
Hi, I'm Tony! I hold a Master of Science (M.S.) degree in Business Analytics from the University of Bath, 
and I am a marketing data analytics manager with 5+ data protection and IT infrastructure industry experiences driving 
business growth and working on high-impact projects on revenue attribution analysis, product optimization, 
churn analysis, customer acquisitions, and more.

<b>
* This repository serves to showcase my data science skills and a way to track my progress in Data Analytics and Data Science-related projects.
</b>

## II. Table of contents
- [About](#i-about)
- [Cybersecurity & Fraud Prevention Projects](#iii-cybersecurity-and-fraud-prevention-projects)
 	+ [1. Credit Fraud Detection](#1-credit-fraud-detection)
  	+ [2. Cybersecurity Threat Analysis](#2-cybersecurity-threat-analysis)
- [Portfolio Projects](#iv-portfolio-projects)
	+ [1. NBA Basketball Sports Analytics - Clustering in ML](#1-nba-basketball-sports-analytics---dissertation-for-university-of-bath-masters-of-business-analytics)
	+ [2. Food Delivery Platform Go-To-Market Strategies - Data Cleaning and Visualization](#2-food-delivery-platform-analysis---go-to-market-strategies)
 	+ [3. Spotify Streaming Analysis - Data Pipeline with AWS](#3-spotify-streaming-analysis-and-data-engineering-with-aws)
	+ [4. Bath Airport Passenger Arrival Simulation and Optimization](#4-bath-airport-passenger-arrival-simulation-and-optimization)
	+ [5. Smartphone User Clustering](#5-smartphone-user-clustering)
	
- [Small Projects](#v-small-projects)
  	+ [1. Building A Retail Data Pipeline](#1building-a-retail-data-pipeline)
  	+ [2. Investigating Netflix Movies](#2investigating-netflix-movies)

- [Certificates](#vi-certificates)
- [Contacts](#vii-contacts)

## III. Cybersecurity and Fraud Prevention Projects

### 1. Credit fraud detection
**Repository:** [`https://github.com/tonychu805/credit_card_fraud_detection`](https://github.com/tonychu805/credit_card_fraud_detection)

**Description:** With a given credit card transaction dataset that has been processed with principal component analysis, the exercise seeks to identify a model that can accurately predict future credict card fraud using machine learning algorithm.

**Skills:** Data cleaning, description analysis, correlation analysis, machine learning

**Technology:** Python, sklearn, Pandas, Numpy, Seaborn, Matplotlib, Logistic Regression, SVM, Random Forest

**Results:** Logistic Regression has the highest predictive power to detect credit card fraud with 95.42% accuracy.

### 2. Cybersecurity Threat Analysis
**Repository:** [`https://github.com/tonychu805/cybersecurity-threat-analysis`](https://github.com/tonychu805/cybersecurity-threat-analysis)

**Description:** In this project, I delved into the patterns and characteristics of vulnerabilities, their severity, the speed of patching, and temporal trends.

**Technology:** Pandas, NumPy, Matplotlib, Seaborn, SciPy, scikit-learn, glob, os

**Results:** 
![image](https://github.com/user-attachments/assets/72696e87-064e-44ff-93e0-a45adbba4ff0)
- Windows is identified as the most affected product with 311 reported vulnerabilities.
- Network-Related vectors accounted for 73.4% of vulnerabilities.
- 34% of the reported incidents were critical, posing severe risks.

## IV. General Projects
In this section, I will list data analytics projects briefly describing the technology stack used to solve cases.

### 1. NBA Basketball Sports Analytics - Dissertation for University of Bath Master's of Business Analytics
**Repository:** [`https://github.com/tonychu805/NBA_Data_Analysis`](https://github.com/tonychu805/NBA_Data_Analysis)
  
**Presentation:** [`Research Paper`](https://github.com/tonychu805/NBA_Data_Analysis/blob/main/Dissertation%20-%20Final%20dissertation.pdf)

**Description:** The three datasets curated and used from Kaggle contain players and games statistics from 1950 to the present, MVP candidates and winners over the years, as well as all shot locations of all games. The project includes the following steps: data loading, data cleaning and preprocessing, filling missing values, EDA (exploratory data analysis), measuring statistical factors, hypothesis testing, and implementing a variety of machine learning algorithms mentioned below.

**Skills:** data cleaning, data analysis, descriptive statistics, central limit theorem, hypothesis testing, data visualization, segmentation analysis, linear regression analysis, support vector machine, random forest, decision trees, principle components analysis,

**Technology:** Python, Pandas, Numpy, Scipy Stats, Seaborn, Matplotlib, Sklearn

**Results:** A deep dive into the impact of three-point shots on the NBA game, user type based on analytics, and prediction of NBA MVPs.  


### 2. Food Delivery Platform Analysis - Go-To-Market Strategies
**Repository:** [`https://github.com/tonychu805/Food_Delivery_Platforms_Analysis`](https://github.com/tonychu805/Food_Delivery_Platforms_Analysis)    

**Presentation:** [`Otter - Case Study Analytics`](https://docs.google.com/presentation/d/1fcv7K0vxSrBWxyRH99rtU1w3BD2VbsgeYe6uky-mt-I/edit?usp=sharing)

**Visualizations:** [`Tableau Dashboard`](https://public.tableau.com/app/profile/tony.chu3466/viz/OtterrestaurantanalysisV2/Dashboard1?publish=yes)

**Description:** Using a food delivery platform dataset in the US containing delivery partners such as Ubereats, Postmates, FoodPanda, and others, I used R language to conduct data cleaning, feature engineering, and exploratory data analysis, while using Tableau to create an interactive dashboard to showcase actionable insights that the delivery analytics product team may take to maximize sales

**Skills:** data cleaning, data analysis, descriptive statistics, central limit theorem, hypothesis testing, data visualization

**Technology:** R, tidyr, dplyr, ggmap, psych, maps, ggplot2, tidygeocoder

**Results:** A thorough analysis of the business operations and performances of each platform among SMBs and enterprise customers, and the recommended go-to actions.  

### 3. Spotify Streaming Analysis and Data Engineering with AWS
**Repository:** [`https://github.com/tonychu805/aws-glue-etl`](https://github.com/tonychu805/aws-glue-etl)    

**Presentation:** [`Spotify Streaming Activities Dashboard (PDF)`](https://github.com/tonychu805/aws-glue-etl/blob/main/AWS-spotify-datapipeline-dashboard.pdf)

**Architecture:** <img width="1395" alt="AWS-spotify-datapipeline-architecture" src="https://github.com/user-attachments/assets/f25cb7a1-3985-49d0-8c64-c71063dd1072">

**Description:** Explore the world of AWS Data Engineering with this project. I leverage AWS services to ingest data, perform ETL processes, run queries, and visualize the findings.

**Skills:** data ingestion, ETL, IAM, feature engineering, data visualization

**Technology:** AWS(S3, Athena, Glue, Quicksight) and Python

**Results:** Constructed a dashboard that is designed to show the marketing and other stakeholders to visualize various streaming activities among Spotify. Stakeholders is able to tell see the number of artists, labels, tracks with explicit language, and the most popular artist at the moment. Some more granular visualization includes the most popular tracks streamed, number of records (by album type) released over time, as well as the number of records included in different album type. Finally, from this chart, the stakeholders can have a holistic view of what the music industry is like at the moment.

### 4. Bath Airport Passenger Arrival Simulation and Optimization
**Repository:** [`https://github.com/tonychu805/bath_airport_simulation`](https://github.com/tonychu805/bath_airport_simulation)    

**Presentation:** [`Otter - Case Study Analytics`](https://docs.google.com/presentation/d/1pn1hxxq-ltGTDHM2UDzShdar2B9wJSWtUuLzLInyePw/edit?usp=sharing)

**Description:** To answer how many passport control gates are needed to make sure that the waiting time in the passport control stage is less than a minute 98% of the time, should the airport combine the check-in desks of different airlines, and is the current allocation of check-in desks and passport control gates ideal?

**Skills:** Data cleaning, data analysis, descriptive statistics, simulation modeling

**Technology:** Python, Seaborn, Matplotlib, Numpy

**Results:** Constructive and actionable insights of how Bath airport can optimize passenger check-in workflow using the detailed outcome of check-in desks’ average wait time, passport gates’ average wait time, total average wait time, and ratio of total passengers who have less than 1 minute of waiting time at the passport gate. 

### 5. Smartphone user clustering
**Repository:** [`https://github.com/tonychu805/smartphone_user_clustering`](https://github.com/tonychu805/smartphone_user_clustering)    

**Presentation:** [`Smartphone user clustering`](https://github.com/tonychu805/smartphone_user_clustering/blob/main/Data%20Mining%20-%20Graded%20Assignment.docx)

**Description:** A handful of exploratory analyses such as identifying missing values and outliers, and exploring correlations of each variable, as well as clustering analyses including partitional clustering, hierarchical clustering, and soft (fuzzy) clustering techniques, are performed among different parameters using R language, to classify, label, or group data points contained within the data set.

**Skills:** Data cleaning, data analysis, descriptive statistics, simulation modeling

**Technology:** R, dplyr, magrittr, ggplot2, tidyverse, finalfit, hmisc, pastecs, psych, corrplot, discriminer, base, reshape2, resample, dendextend, fpc, dbscan

**Results:** Three naturally occurring clusters are ultimately identified. However, further analyses of each identified cluster will need to be conducted if the management would like to learn more about each of its characteristics.


## V. Small Projects
In this section, I will list smaller scale data analytics projects and exercises.

### 1.	Building a retail data pipeline
**Repository:** [`https://github.com/tonychu805/building-a-retail-data-pipeline`](https://github.com/tonychu805/building-a-retail-data-pipeline)

**Description:** Created a data pipeline for the analysis of supply and demand around the holiday seasons, and generated a monthly sale out report.

### 2.	Investigating Netflix Movies
**Repository:** [`https://github.com/tonychu805/investigating-netflix-movies`](https://github.com/tonychu805/investigating-netflix-movies)

**Description:** Created a data pipeline for the analysis of supply and demand around the holiday seasons, and generated a monthly sale out report.

## VI. Certificates
Here is a list of the data analytics certificates and programs that I have completed over the years:
- [Introduction to Git](https://www.datacamp.com/statement-of-accomplishment/course/95e4d09c9a5127c7839885c159ae188f6813cfd6?raw=1) (July 2024)(Datacamp)
- [Streamlined data ingestion with Python](https://www.datacamp.com/statement-of-accomplishment/course/858312c1f72afb737ba60ebdf7d5bb89fd108aab?raw=1) (June 2024)(Datacamp)
- [Writing efficient Python code](https://www.datacamp.com/statement-of-accomplishment/course/10398bf7737fef0878d5b26a72cfbfae97509e5f?raw=1) (June 2024)(Datacamp)
- [Cleaning Data in Python](https://www.datacamp.com/statement-of-accomplishment/course/88aefd54042e2d5ade1956d625bd3b83238ccdaa?raw=1) (June 2024)(Datacamp)
- [Intermediate importing data in Python](https://www.datacamp.com/statement-of-accomplishment/course/ffbfe5e9b728374eb5048ea9063e31e5a51d4830?raw=1) (June 2024)(Datacamp)
- [Introduction to importing data in Python](https://www.datacamp.com/statement-of-accomplishment/course/0b930ab45acfc5e8c9924fc5990aefac92898d9e?raw=1) (June 2024)(Datacamp)
- [Intermediate Python for developers](https://www.datacamp.com/statement-of-accomplishment/course/4b49c3da62318e40a7da8e50f5d561691798e44e?raw=1) (June 2024)(Datacamp)
- [Introduction to Python for developers](https://www.datacamp.com/statement-of-accomplishment/course/4edbc50773418dd73ba390048e63343913000c49?raw=1) (June 2024)(Datacamp)
- [Understanding Cloud Computing](https://www.datacamp.com/statement-of-accomplishment/course/6a64174eb9052c1e85e0dc0f93bab63f1889ecaf?raw=1) (June 2024)(Datacamp)
- [Associate Data Analyst](https://www.datacamp.com/statement-of-accomplishment/track/a7711e752f6aa5f43c0a8e276f44296897e12d2b?raw=1) (May 2024)(Datacamp)
- [Understanding Data Visualization](https://www.datacamp.com/statement-of-accomplishment/course/b756afe279ad16e20ed40e37c4a66573d593f440?raw=1) (May 2024)(Datacamp)
- [Functions for Manipulating Data in PostgreSQL](https://www.datacamp.com/statement-of-accomplishment/course/0ae6a0684b420d5434e88b7e0f7399d7a5a51671?raw=1) (May 2024)(Datacamp)
- [PostgreSQL Summary Stats and Window Functions](https://www.datacamp.com/statement-of-accomplishment/course/b13d67e4e108b54cf8c35f905e2637df39287291?raw=1) (May 2024)(Datacamp)
- [Enterprise Design Thinking Practitioner](https://www.credly.com/badges/22580781-6bd7-4c2b-a3bd-7bfdbfdb88d6/public_url) (Mar 2022)(IBM)
- [Python + SQL + Tableau: Integrating Python, SQL, and Tableau](https://www.udemy.com/certificate/UC-bdd36dc1-19d0-42e8-8e8e-7b66ca8e36b0/) (Mar 2020)(Udemy)
- [Analytics: Essential Tools and Methods MicroMaster](https://credentials.edx.org/credentials/6eb5a4245dcd4348ba175be67a07152c) (Dec 2019)(Georgia Tech)
- [Computing for Data Analysis](https://courses.edx.org/certificates/e771a69c972242ba9a78e06ad3974701) (Dec 2019)(Georgia Tech)
- [Data Analytics for Business](https://courses.edx.org/certificates/d83707bc38b54cacbc7283593b4c6a91) (Dec 2019)(Georgia Tech)
- [Introduction to Analytics Modeling](https://courses.edx.org/certificates/eeb48e32c0044448bccedacd50773eac) (May 2019)(Georgia Tech)
- [SQL - MySQL for Data Analytics and Business Intelligence](https://udemy-certificate.s3.amazonaws.com/pdf/UC-0BTWQELU.pdf) (Jul 2019)(Udemy)
- [Master Excel Pivot Table](https://www.udemy.com/certificate/UC-GJ31OB9G/) (Nov 2016)(Udemy)
- [Complete SQL Bootcamp](https://udemy-certificate.s3.amazonaws.com/pdf/UC-E05IGQ0Q.pdf) (Oct 2016)(Udemy)
- [Intro to Programming Nanodegree](https://confirm.udacity.com/WM9YRAFX) (Sep 2016)(Udacity)
- [SQL for Beginner Data Analysis](https://udemy-certificate.s3.amazonaws.com/pdf/UC-7OUXO2ZH.pdf) (Jul 2016)(Udemy)
- [Big Data and Hadoop Essentials](https://www.udemy.com/certificate/UC-IX3PT0YD/) (May 2016)(Udemy)



## VII. Contacts
- LinkedIn: [@tonychu805](https://www.linkedin.com/in/tonychu805/)
- E-mail: tony.chu805@gmail.com
