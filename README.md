Project Overview: Understanding the Basics and Goals
The goal of this project is to build a robust machine learning model capable of detecting fraudulent credit card transactions. Credit card fraud is a growing concern in today's increasingly digital financial landscape, leading to significant financial losses for both consumers and financial institutions.

This project focuses on analyzing a real-world dataset of credit card transactions in the US to uncover patterns indicative of fraudulent activity. Through:

- 📊 Exploratory Data Analysis
- 🛠️ Feature Engineering
- 🤖 Machine Learning Modeling
● What are we trying to find out?
We aim to identify whether a transaction is fraudulent based on transaction metadata and user behavior.
● What do we already know?
We know that fraud is rare compared to legitimate transactions, approx 0.5% of credit card transactions are fraudulent making this a highly imbalanced classification challenge. Fraudulent behavior often exhibits patterns like abnormal transaction times, high-value amounts, geographic anomalies and combinations between them e.g. a senior customer is less likely to perform transactions at certain amounts and times of the day.
● What are we aiming to achieve?
Our goal is to accurately detect fraudulent transactions while minimizing false positives to avoid disrupting genuine users.
● What factors affect our results?
Class imbalance, feature quality, model selection, model parameters, and evaluation metrics all significantly influence the final model's effectiveness.
● Is there something new we can use?
Yes. We explore advanced ensemble models like XGBoost, feature interaction engineering, and resampling strategies (SMOTE, SMOTETomek) to counter imbalance for the end goal os enhancing prediction accuracy and generalization.

● Accompanying project document, **Credit_Card_Fraud_Detection_Overview.pdf**

● Project runing environment setup exported to **ds18_env_29.03.25.yml** (conda env create -f ds18_env_29.03.25.yml -n myenvname) 

● Project data, some of the project data files (csv & pickle) are too large to manage on Github, files are downloadavle aldo from google drive:
[Download Dataset from Google Drive](https://drive.google.com/drive/folders/1fj5W9gTy1bmbCPMZOGqFl2iCZmKMsAs-?usp=sharing)

