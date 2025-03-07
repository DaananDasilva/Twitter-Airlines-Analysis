# Twitter Data Analysis for Airlines

## Overview
This project analyzes Twitter sentiment for US airlines, focusing on Delta Airlines, using the "Twitter US Airline Sentiment" dataset from Kaggle. It employs sentiment classification, topic modeling, and visualizations to uncover customer feedback trends and provide business recommendations.

## Objectives
- Classify tweet sentiment (positive, negative, neutral) using a logistic regression model.
- Identify key complaint and appreciation themes via LDA topic modeling.
- Compare Delta Airlines’ sentiment with competitors and recommend service improvements.

## Approach
1. **Data Cleaning**: Processed tweets with custom text cleaning (e.g., removing URLs, emojis to text).
2. **Sentiment Analysis**: Trained a Logistic Regression model with TF-IDF features (78% accuracy).
3. **Topic Modeling**: Used LDA to extract complaint and praise topics.
4. **Visualization**: Created bar charts, pie charts, and word clouds for insights.

## Key Insights
- Delta has a 48.5% negative sentiment rate, better than United (72.8%) but worse than Virgin America (45.2%).
- Top complaints: flight delays, cancellations, baggage issues, poor customer service.
- Positive feedback: good in-flight experience and responsive support.

## Tools Used
- Python (Pandas, NLTK, Gensim, Scikit-learn)
- Visualization (Matplotlib, Seaborn, pyLDAvis)

## Recommendations
- Improve flight delay communication with real-time updates.
- Enhance baggage tracking and customer service response times.

## How to Run
1. Clone the repo
2. Install dependencies
3. Run the notebook
