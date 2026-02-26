#  Sentiment Analysis of Amazon Mobile Phone Reviews Using Python & TextBlob

##  Project Overview

This project implements an automated sentiment analysis system to classify 1,448 Amazon mobile phone reviews into three categories: Positive, Neutral, and Negative using Natural Language Processing (NLP).

The system calculates polarity scores using TextBlob and applies custom classification thresholds to generate data-driven insights that support e-commerce decision-making.

---
## Project Structure

Building-a-Basic-Sentiment-Analyzer-with-Python-and-TextBlob/

├── images/                          # Visualization outputs
│   ├── sentiment-bar-chart.png      # Bar chart of sentiment distribution
│   ├── sentiment-pie-chart.png      # Pie chart of sentiment percentages
│   └── polarity-histogram.png       # Polarity score distribution histogram
│
├── Building a Basic Sentiment Analyzer with Python & TextBlob.ipynb
│                                       # Main Jupyter Notebook (data processing & analysis)
│
└── README.md                         # Project documentation




##  Business Problem

Amazon sellers face challenges when manually analyzing large volumes of customer reviews. This process is time-consuming and makes it difficult to identify recurring issues and overall customer satisfaction trends.

This project provides an automated solution to:

- Measure overall customer satisfaction  
- Detect recurring product issues  
- Support data-driven improvement decisions  

---

## 📊Key Results

- Analyzed 1,448 customer reviews  
- 53.04% Positive reviews  
- 39.36% Neutral reviews  
- 7.60% Negative reviews  
- Examined 110 negative reviews to identify major product concerns  
- Generated visual insights using bar charts, pie charts, and polarity distribution histograms  

---

##  Tech Stack

- Language: Python 3.x  
- Libraries: Pandas, NumPy, TextBlob, Matplotlib, NLTK  
- Dataset Source: Kaggle (Amazon Unlocked Mobile Phones Reviews)

---

##  Methodology

1. Dataset acquisition using KaggleHub  
2. Data cleaning and review text preprocessing  
3. Custom sentiment classification based on polarity thresholds:
   - Polarity < -0.2 → Negative  
   - -0.2 ≤ Polarity ≤ 0.2 → Neutral  
   - Polarity > 0.2 → Positive  
4. Sentiment distribution analysis and visualization  

---

##  Project Context

Developed as part of ARTI 402 – Programming for AI  
Imam Abdulrahman Bin Faisal University  

Role: Sentiment Model Development & Data Analysis
