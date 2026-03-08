# AI-Based Phishing Website Detection

## Project Overview
Phishing websites are a common cybersecurity threat where attackers mimic legitimate websites to steal sensitive user information.  
This project applies machine learning techniques to detect phishing websites by analyzing URL-based features.

The goal of the project is to build and evaluate classification models that can automatically determine whether a given URL is **phishing or legitimate**.

---

## Dataset
The dataset used in this project contains both **phishing URLs and legitimate URLs**.

Sources include publicly available cybersecurity datasets such as:

- PhishTank phishing URL feeds
- Open security datasets containing legitimate website URLs

A combined dataset of **10,000 URLs** was prepared for training and testing.

---

## Feature Extraction
From each URL, several features were extracted to represent the characteristics of phishing websites.

The extracted features belong to the following categories:

### Address Bar Based Features
Examples include:
- URL length
- Presence of special characters
- Use of IP addresses instead of domain names

### Domain Based Features
Examples include:
- Domain age
- Domain registration length
- DNS record availability

### HTML and JavaScript Based Features
Examples include:
- Presence of suspicious scripts
- Redirection behavior
- Use of iframe elements

In total **17 features** were extracted from the dataset.

---

## Machine Learning Models
This project evaluates multiple supervised machine learning models for phishing detection:

- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Multilayer Perceptron (Neural Network)
- XGBoost Classifier
- Autoencoder Neural Network

The dataset was split into:

- **80% Training Data**
- **20% Testing Data**

Each model was trained and evaluated using classification metrics.

---

## Results
Among the evaluated models, **XGBoost achieved the highest accuracy of approximately 86%** in detecting phishing websites.


## Author
Atharv Patil  
