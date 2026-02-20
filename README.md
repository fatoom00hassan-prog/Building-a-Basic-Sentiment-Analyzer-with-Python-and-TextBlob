
# Sentiment Analysis of Amazon Mobile Phone Reviews using Python & TextBlob

##  Project Description

This project presents the development of a basic Sentiment Analysis model using Python and TextBlob to classify Amazon mobile phone reviews into three sentiment categories: Positive, Neutral, and Negative.

Customer reviews represent a valuable source of information regarding product quality, performance, and user satisfaction. However, manually analyzing large volumes of textual feedback is inefficient and time-consuming.
To address this challenge, this project applies Natural Language Processing (NLP) techniques to automatically evaluate review sentiment through polarity scoring.
The model calculates polarity scores using TextBlob and assigns sentiment labels based on custom-defined threshold ranges. 
This implementation demonstrates a rule-based sentiment classification approach and highlights how lightweight NLP libraries can be effectively used to extract meaningful insights from real-world textual data.

---

##  Project Objective
The main objectives of this project are:

- Understand the fundamentals of Natural Language Processing (NLP)
- Implement polarity-based sentiment classification
- Work with real-world customer review data
- Apply threshold-based decision logic
- Visualize sentiment distribution using data analysis tools

---

##  Technologies Used

- Python
- TextBlob
- Pandas
- Matplotlib
- NLTK
- KaggleHub

---

##  Dataset Details
- Source: Kaggle
- Dataset: Amazon Reviews (Unlocked Mobile Phones)
- Type: Customer review text data
- Access Method: The dataset is automatically downloaded using KaggleHub when running the notebook.



---

##  Methodology
1. The dataset was downloaded using KaggleHub.
2. Review text data was extracted and prepared.
3. A custom sentiment classification function was implemented.
4. TextBlob polarity scores were calculated for each review.
5. Reviews were categorized based on the following thresholds:
   - Polarity < -0.2 → Negative
   - -0.2 ≤ Polarity ≤ 0.2 → Neutral
   - Polarity > 0.2 → Positive
6. Sentiment distribution was analyzed and visualized using Matplotlib.

## Project Context

This project was developed as a group assignment for the course ARTI 402 – Programming for AI at Imam Abdulrahman Bin Faisal University.

My Role: Sentiment Model Development & Analysis

