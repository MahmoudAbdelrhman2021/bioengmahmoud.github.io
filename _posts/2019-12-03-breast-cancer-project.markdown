---
title: "Breast Cancer Classification with Machine Learning"
layout: post
date: 2019-12-03 10:55
image: /assets/images/markdown.jpg
headerImage: false
tag:
- R
- Breast Cancer
- Machine Learning
star: true
category: blog
projects: true
hidden: true
author: Mahmoud Abdelrhman
description: A binary classification to predict whether a patient dies within five years or survives.
---

## Introduction

My group and I studied for the first time a biostatistics course within this academic semester of our third year in the college. Within this course we had to adapt with a project in this subject and that was in machine learning. It was our first time to study machine learning and to deal with this task which is consisting of many algorithms, deep learning and data science. We did our best to keep in touch with this situation to learn and discover ourselves in this track. Our project was a binary classification to predict whether a patient dies within five years or survives.

---

## Purpose

For our society, expecting the survival status of patients who will undertake breast cancer surgery is highly vital, where it speciﬁes whether conducting a surgery is the best solution for the presented medical case or not. The need to explore better prediction techniques to ensure accurate survival status prediction cannot be overemphasized. We would like to explain the various data analysis operation that we would do on this data set and how to conclude or predict survival status of patients who undergone from surgery.

---

## Data & Methodology

Age of patient at time of operation (numerical), patient’s year of operation (year-1900, numerical), number of positive auxiliary nodes detected (numerical), and also survival status (class attribute) which divides into the patient survived within 5 years or longer or the patient died. So, we have 3 features with 306 examples.
We studied a series of asking questions and applying questions and to uncover the hidden insights from the data. A case study on the cancer survival data set was done to explore the most common EDA techniques in this blog. 
The ﬁeld of data science has progressed from simple linear regression models to complex assembling techniques but the most preferred models are still the simplest and most interpretable. Among them were Logistic regression, Decision Trees, K-nearest neighbors (KNN) model, Kernel and naïve bayes techniques. We used these different methods and did our study. After that we compared with them to know which one is the best method for our project. 

---
## Pre-Processing

![Markdowm Image][1]


We detected if we would make some feature selections or not according to EDA and our visualization. We selected the previous 5 methods Naive Bayes (NB) Classier, K-nearest neighbors (KNN) model, Decision Trees, Logistic Regression and Kernel after that we didn't need to make some standardizations at each method. No imputation was found as we didn’t have any missing data.

---

## Summary

We were facing a challenge which was a case of life or death. Cataloguing of Haberman’s survival information was beneﬁcial to realize the patients’ survival probability after a breast cancer surgery. We depended on a collected dataset from a standard benchmark UCI machine learning repository. We were trying to get through data imputation, categorical datatype, data processing and exploratory data analysis using different methodologies to detect the performance evaluation of classiﬁers and to compare between them to find the most suitable one.

---

[1]: https://bioengmahmoud.github.io/assets/images/graphs.png