# Sentiment Analysis Techniques Comparison

This repository contains a comprehensive analysis and comparison of three popular sentiment analysis techniques: VADER (Valence Aware Dictionary and sEntiment Reasoner), the Roberta Pretrained Model from Hugging Face, and the Huggingface Pipeline. The project aims to provide insights into the accuracy, processing speed, and overall performance of each approach, helping users make informed decisions for sentiment analysis tasks.

## Table of Contents

- [Step 0: Read in Data and NLTK Basics](#step-0-read-in-data-and-nltk-basics)
- [Quick Exploratory Data Analysis (EDA)](#quick-eda)
- [Basic NLTK Usage](#basic-nltk)
- [Step 1: VADER Sentiment Scoring](#step-1-vader-sentiment-scoring)
- [Step 2: Plot VADER Analysis Results](#step-2-plot-vader-analysis-results)
- [Step 3: Roberta Pretrained Model](#step-3-roberta-pretrained-model)
- [Step 4: Compare Scores Between Models](#step-4-compare-scores-between-models)
- [Step 5: Combine and Compare Approaches](#step-5-combine-and-compare-approaches)
- [Step 6: Review Examples](#step-6-review-examples)
- [Step 7: The Transformers Pipeline](#step-7-the-transformers-pipeline)
- [Step 8: Combining Approaches and Comparing Efficiency](#step-8-combining-approaches-and-comparing-efficiency)
- [Final Results and Recommendations](#final-results-and-recommendations)

## Introduction

Sentiment analysis involves determining the emotional tone of a text, whether it's positive, negative, or neutral. In this project, we explore three distinct sentiment analysis techniques and evaluate their efficacy across a variety of criteria.

## Technologies and Libraries

- NLTK: Used for VADER's lexicon-based approach.
- Hugging Face Transformers: Utilized the Roberta Pretrained Model for deep learning-based sentiment analysis.
- Huggingface Pipeline: Employed for efficient sentiment predictions without complex setup.
- Pandas: Data manipulation and analysis.
- Seaborn and Matplotlib: Data visualization.

## Project Highlights

- **Accuracy Comparison**: We analyzed the accuracy of each approach on a dataset containing various sentiment-labeled texts.
- **Speed Comparison**: Processing times for each approach were measured to assess their efficiency.
- **Graphical Representations**: Utilized Seaborn and Matplotlib to create insightful visualizations.
- **Data set**: https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews
- **Conclusion**: Summarized the findings and provided recommendations based on the comparative analysis.

## Results and Insights

- The Huggingface Pipeline approach demonstrated the highest accuracy (96.40%), making it ideal for precise sentiment analysis tasks.
- The Roberta Pretrained Model showcased competitive accuracy (80.80%) while offering customization potential.
- VADER, despite its simpler lexicon-based method, still achieved decent accuracy (77.80%) and is suitable for quick assessments.
- The Huggingface Pipeline is particularly recommended for real-time applications requiring accurate sentiment predictions.

## Usage

To replicate and explore the project:

1. Clone this repository: `git clone https://github.com/yourusername/sentiment-analysis-comparison.git`
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the analysis script: `python analyze_sentiment.py`

## Conclusion

This project provides valuable insights into the strengths and weaknesses of three sentiment analysis techniques. By comprehensively evaluating accuracy, speed, and performance, we empower users to choose the optimal approach based on their specific project requirements. The diverse toolkit of technologies and libraries used in this analysis underscores the importance of selecting the right tool for the task at hand, ensuring accurate and efficient sentiment analysis of textual data.
