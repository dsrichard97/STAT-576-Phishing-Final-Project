# STAT-576-Phishing-Final-Project

## Table of Contents
- [Introduction](#Introduction)
- [About the Data](#About-The-Data)
- [Methodology](#Methods)
  - [Data Preprocessing](#Data-Preprocessing)
  - [Feature Selection](#Feature-Selection)
  - [Outputs](#Outputs)
  - [Remarks](#Remarks)
- [Conclusion](#Conclusion)
- [References](#References)


# Introduction
A final project authored by Cory Suzuki, Nathaniel Talampas, and Richard Diaz DeLeon for Dr. Seungjoon Lee's Unsupervised Learning class. Here we perform dimensionality reduction techniques for feature extraction and utilize clustering methods to analyze insightful trends on the classification of phishing and scam emails.

# Motivation
In today's digital age, phishing attacks have become a major threat to individuals and organizations alike. These attacks exploit users' trust, resulting in significant financial losses and breaches of sensitive information. To address this widespread issue, it is crucial to develop effective methods for identifying and mitigating phishing attempts.



## About-The-Data
The Phishing URL Dataset consists of URLs labeled as either phishing or legitimate. Phishing URLs are designed to deceive users into providing sensitive information, such as usernames and passwords, often mimicking legitimate sites. Data can be found at the following link: https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+dataset

## Methods
- FEATURE SELECTION
- FEATURE SELECTION BY CORRELATION
- DIMENSIONALITY REDUCTION
- LINEAR TECHNIQUES
- NON-LINEAR TEHCHNIQUES

# Data-Preprocessing
From UCI repo we can get the following dtaa by applying python code to fetch the data
```python
from ucimlrepo import fetch_ucirepo 

# fetch dataset 
phiusiil_phishing_url_website = fetch_ucirepo(id=967) 

# data (as pandas dataframes) 
X = phiusiil_phishing_url_website.data.features 
y = phiusiil_phishing_url_website.data.targets 

# metadata 
print(phiusiil_phishing_url_website.metadata) 

# variable information 
print(phiusiil_phishing_url_website.variables) 
```

# Feature-Selection
![correlation](/workspaces/STAT-576-Phishing-Final-Project/output.png)

From the correlation matrix we can get the following reduction to get our outputs.


# Outputs
![picture](output2.png)

![picture](output3.png)

![picture](lle.png)

![picture](iso1.png)











