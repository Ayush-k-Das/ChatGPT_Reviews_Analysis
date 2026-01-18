# 📊 ChatGPT Reviews Analysis

A comprehensive **sentiment and user feedback analysis** project on **ChatGPT app reviews**, leveraging **Natural Language Processing (NLP)** and **interactive visualizations** to uncover user satisfaction trends, common feedback themes, and overall Net Promoter Score (NPS).

---

## 📌 Project Overview

This project analyzes **196,000+ user reviews** of ChatGPT to:

* Understand overall **sentiment distribution**
* Identify **common positive and negative feedback themes**
* Track **sentiment trends over time**
* Calculate **Net Promoter Score (NPS)** to measure user loyalty

The analysis combines **text processing, sentiment analysis, n-gram phrase extraction**, and **interactive Plotly visualizations**.

---

## 🧠 Key Objectives

* Perform exploratory data analysis (EDA) on large-scale review data
* Classify reviews into **Positive, Neutral, and Negative** sentiments
* Extract frequently occurring phrases from reviews
* Identify major problem categories faced by users
* Analyze sentiment evolution over time
* Measure customer satisfaction using **Net Promoter Score (NPS)**

---

## 🗂 Dataset Information

* **Source**: ChatGPT Reviews Dataset
* **Records**: 196,727
* **Columns**:

  * `Review Id`
  * `Review`
  * `Ratings`
  * `Review Date`

---

## 🔍 Methodology

### 1️⃣ Data Preprocessing

* Handled missing values in review text
* Converted date fields to datetime format
* Standardized text data for analysis

### 2️⃣ Sentiment Analysis

* Used **TextBlob** polarity scores
* Classified reviews into:

  * Positive
  * Neutral
  * Negative

### 3️⃣ Exploratory Data Analysis (EDA)

* Sentiment distribution visualization
* Monthly sentiment trends over time
* Ratings distribution analysis

### 4️⃣ Text Mining & NLP

* Extracted **bi-grams and tri-grams** using `CountVectorizer`
* Identified top phrases in:

  * Positive reviews
  * Negative reviews

### 5️⃣ Problem Categorization

Grouped negative feedback into:

* Incorrect Answers
* App Performance Issues
* User Interface Problems
* Missing / Broken Features
* Poor Response Quality

### 6️⃣ Net Promoter Score (NPS)

* Promoters: Rating = 5
* Passives: Rating = 4
* Detractors: Rating ≤ 3

**Final NPS Score:**

> ⭐ **64.35 (Excellent user satisfaction)**

---

## 📈 Key Insights

* Majority of users express **positive sentiment**
* High ratings dominate the dataset
* Common praise revolves around **accuracy and usefulness**
* Negative feedback mainly relates to:

  * Incorrect answers
  * Performance issues
  * Feature limitations
* Sentiment trends show **consistent positive engagement over time**
* NPS above 50 indicates **strong brand advocacy**

---

## 🛠️ Technologies Used

* **Python**
* **Pandas & NumPy**
* **TextBlob (Sentiment Analysis)**
* **Scikit-learn (CountVectorizer)**
* **Plotly & Plotly Express (Interactive Visualizations)**

---

## 📊 Visualizations Included

* Sentiment distribution bar chart
* Top phrases in positive reviews
* Top phrases in negative reviews
* Common user problem categories
* Monthly sentiment trend analysis
* NPS calculation summary

---

## 🚀 How to Run the Project

```bash
# Clone the repository
git clone https://github.com/your-username/chatgpt-reviews-analysis.git

# Install required libraries
pip install pandas numpy textblob scikit-learn plotly

# Run the notebook
jupyter notebook
```

---

## 📌 Project Use Cases

* Customer sentiment monitoring
* Product feedback analysis
* App review intelligence
* NLP & text analytics portfolio project
* Data Analyst / ML Engineer showcase

---

## ⭐ If you found this project useful

Consider giving the repository a ⭐ to support the work!

---
