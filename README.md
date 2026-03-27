# YouTube Comment Sentiment Analysis (NLP)

This project analyzes YouTube comments from a tech review video (MKBHD Galaxy Ring review) using Natural Language Processing (NLP) techniques.

## Project Overview
- Collected YouTube comments using YouTube Data API
- Cleaned and preprocessed text data
- Converted text into numerical features using TF-IDF
- Built a sentiment classification model
- Visualized common words using WordCloud
- Applied topic modeling (LDA) on negative comments

## Tech Stack
- Python
- Pandas
- NLTK
- Scikit-learn
- Matplotlib
- WordCloud

## Model Approach
- Text data was transformed using TF-IDF vectorization
- A machine learning classifier was trained to distinguish sentiment patterns
- The model was evaluated based on how well it separated positive and negative comment patterns

## Key Insights
- Word frequency analysis showed commonly discussed features in the product
- Negative comments were further analyzed using topic modeling to identify recurring concerns
- The model was able to capture general sentiment trends from user comments

## Important Note
- Sentiment labels were generated using a simple rule-based approach (based on keyword presence)
- This project is focused on learning and demonstrating NLP workflow rather than achieving production-level accuracy

## Outcome
This project helped me understand:
- Text preprocessing in NLP
- Feature extraction using TF-IDF
- Building a basic sentiment analysis pipeline
- Extracting insights from unstructured text data

---
