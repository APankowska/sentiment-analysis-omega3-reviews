# Sentiment Analysis of Omega-3 Supplement Reviews
Sentiment analysis of customer reviews for omega-3 dietary supplements using NLP techniques in R. The project focuses on health-related review text and customer perceptions expressed in online product feedback.

## Project Overview

This project presents a comprehensive sentiment analysis of online consumer reviews of selected omega-3 dietary supplements. The aim was to explore how users express opinions about health-related products and to identify key factors influencing overall sentiment.

The analysis combines exploratory data analysis (EDA), lexicon-based sentiment analysis, and topic modeling, providing both quantitative and qualitative insights into customer feedback. The project was conducted as part of an MSc Data Science thesis and adapted here for portfolio presentation.

## Problem Context & Motivation

Online reviews of dietary supplements play a significant role in consumer decision-making, particularly in the health domain where product effectiveness and side effects are highly subjective. However, sentiment analysis in this context is challenging due to domain-specific language, implicit health claims, and the frequent use of mixed or neutral expressions.

Understanding which product features drive positive or negative sentiment can support both consumers and manufacturers by improving transparency, product development, and quality assessment. This project aims to address these challenges by combining exploratory analysis, lexicon-based sentiment scoring, and topic modeling to extract interpretable insights from real user reviews.

## Objectives

The main objectives of the project were:
 - To identify the overall sentiment distribution of omega-3 supplement reviews
 - To determine which product features are most frequently praised or criticized
 - To explore key themes discussed by users using topic modeling
 - To examine the relationship between sentiment polarity and star ratings (1–5)
   
These objectives correspond directly to the thesis research questions.

## Dataset

The dataset consists of user-generated reviews collected from online retail platforms. 
Each record includes:
 - Review text
 - Numerical rating (1–5 stars)
   
The data represents real consumer opinions related to effectiveness, side effects, taste, packaging, and perceived health benefits.

## Data Preprocessing

Before analysis, the textual data underwent standard NLP preprocessing steps:
 - Removal of duplicates
 - Lowercasing text
 - Removal of punctuation, numbers, and special characters
 - Tokenization
 - Stop-word removal
 - Lemmatization
   
These steps ensured cleaner input for sentiment analysis and topic modeling.


## Exploratory Data Analysis

EDA was performed to understand the structure and characteristics of the dataset.
Key analyses included:
 - Distribution of star ratings
 - Review length analysis
 - Frequency of most common words
 - Initial inspection of sentiment tendencies across ratings
   
The EDA revealed a strong imbalance toward positive reviews, which is common in health-related consumer products.

## Sentiment Analysis

A lexicon-based sentiment analysis approach was applied to classify reviews as:
 - Positive
 - Neutral
 - Negative
   
Sentiment scores were calculated based on word polarity values, and each review was assigned an overall sentiment label.
The results showed:
 - A clear dominance of positive sentiment
 - Negative sentiment often linked to side effects, fishy aftertaste, or capsule size
 - Neutral reviews typically describing factual usage without strong emotional tone

## Topic Modeling

Topic modeling was conducted to identify main themes present in the reviews.
The analysis revealed recurring topics such as:
 - Product effectiveness and health benefits
 - Taste and smell
 - Capsule size and ease of swallowing
 - Price and value for money
 - Delivery and packaging quality
   
These topics aligned strongly with sentiment polarity, helping explain why certain reviews were positive or negative.

## Results 

Key findings of the project include:
 - Positive sentiment strongly correlates with higher star ratings
 - Health benefits and perceived effectiveness are the most influential factors driving positive reviews
 - Negative reviews are primarily associated with physical discomfort or sensory issues
 - Topic modeling provided valuable interpretability by linking sentiment scores with concrete product features
   
Overall, the study confirms that sentiment analysis can effectively capture consumer attitudes toward dietary supplements, though domain-specific language plays a crucial role in interpretation.

## Limitations



## Conclusions & Future Work



## Tools & Technologies
 - R (text mining, sentiment analysis, topic modeling)
 - NLP libraries for preprocessing and analysis
 - Statistical methods for exploratory analysis




