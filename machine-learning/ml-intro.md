---
layout: default
title: "Basic Questions About Machine Learning"
date: 2025-11-02
excerpt: "A beginner-friendly guide to common questions about Machine Learning."
---

<p align="center">
  <img src="../assets/ml-overview.png" width="30%" alt="Machine Learning Overview">
</p>

## How can we describe machine learning?

A data-driven process of improving inference, prediction, and decision-making capabilities.

---

## When should we use machine learning?

We use machine learning when:

- The process involves a lot of complex or hard-to-define rules  
- The problems are mixed, ill-structured, or unstructured  
- The solutions involve big data  
- The environment is dynamic and constantly changing, requiring adaptive responses  
- We need to discover patterns or gain new insights from the data

---

## What is labeled data?

Labeled data refers to data that has been annotated with labels that describe its meaning, category, or outcome.

---

## What are the most common challenges or weaknesses in machine learning?

- Missing or incomplete data  
- Low-quality or noisy data  
- Data not representing the actual problem  
- Uninformative features (bilgilendirici olmayan özellikler)  
- Overfitting / Underfitting  

---

## What are the definitions of Training, Validation, and Test Datasets?

### 🧠 Training Dataset — where the model learns

The training dataset is the data used to teach the machine learning model.  
It contains input samples along with their correct output labels.  
The model learns patterns and relationships by adjusting its internal parameters based on this data.

---

### ⚙️ Validation Dataset — where we check the model’s progress and fine-tune it

The validation dataset is a separate subset used during the training process to assess how well the model is performing on unseen data.  
It helps in tuning hyperparameters (like learning rate, model complexity) and in making decisions such as when to stop training (to avoid overfitting).

---

### 🔍 Test Dataset — where we verify how well the model will perform on completely new, unseen data

The test dataset is a distinct set of data reserved for final evaluation of the trained model.  
It measures the model’s ability to generalize to completely new data and provides an unbiased assessment of its real-world performance.
