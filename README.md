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

The ['dataset'](https://github.com/APankowska/sentiment-analysis-omega3-reviews/blob/main/Supplement%20Data%20Omega%203.csv) consists of user-generated reviews collected from online retail platforms. 
Each record includes:
 - Review text
 - Numerical rating (1–5 stars)
   
The data represents real consumer opinions related to effectiveness, side effects, taste, packaging, and perceived health benefits.

## Data Preprocessing

Before analysis, the textual data underwent standard NLP preprocessing steps:
 - Removal of duplicates
 - Removal of punctuation, numbers, and special characters
 - Lowercasing text
 - Tokenization
 - Stop-word removal
 - Lemmatization
   
These steps ensured cleaner input for sentiment analysis and topic modeling.


## Exploratory Data Analysis

EDA was performed to understand the structure and characteristics of the dataset.
Key analyses included:
 - Distribution of star ratings ['Distribution'](https://github.com/APankowska/sentiment-analysis-omega3-reviews/blob/main/Rating%20distribution.pdf)
 - Review length analysis  ['Review length']
 - Frequency of most common words ['Word cloud']
 - Initial inspection of sentiment tendencies across ratings ['Sentiment vs. Rating']
   
The EDA revealed a strong imbalance toward positive reviews, which is common in health-related consumer products.

## Sentiment Analysis

A lexicon-based sentiment analysis approach was applied to classify reviews as:
 - Positive
 - Neutral
 - Negative
   
Sentiment scores were calculated based on word polarity values, and each review was assigned an overall sentiment label.

The results showed:
 - A clear dominance of positive sentiment
 - Positive sentiment mainly relates to effectiveness and service
 - Negative sentiment often linked to side effects, fishy aftertaste, or capsule size
 - Negative opinions tend to appear in longer reviews

## Topic Modeling

Topic modeling was conducted to identify main themes present in the reviews.

The analysis revealed recurring topics such as:
 - Product effectiveness and health benefits
 - Taste and smell
 - Capsule size and ease of swallowing
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

Despite providing meaningful insights, this study has several limitations that should be acknowledged.

First, sentiment analysis was performed using a lexicon-based approach, which may not fully capture contextual meaning, sarcasm, or nuanced emotional expressions present in user-generated reviews. As a result, some sentiment scores may not perfectly reflect the true intent of the reviewers.

Second, the analysis was conducted on a limited set of omega-3 supplements. While this allowed for detailed exploration, the findings may not be fully generalisable to all dietary supplements or broader consumer markets.

Additionally, numerical ratings were treated as direct indicators of customer satisfaction. However, ratings do not always align with the emotional tone of written reviews, as users may express mixed or contradictory sentiments within the same review.

Finally, preprocessing steps such as stop-word removal and token filtering, although necessary, may have removed potentially meaningful contextual information, influencing topic modelling and sentiment interpretation.

## Conclusions & Future Work

The aim of this study was to determine overall consumer sentiment by analysing numerical ratings and textual content in online reviews of omega-3 supplements.

The findings show that sentiment analysis is a useful tool for identifying key themes and emotional tone in consumer reviews. The analysis revealed a moderate positive relationship between numerical ratings and sentiment scores, indicating that higher ratings are generally associated with more positive sentiment expressed in review content.
However, the results also demonstrate that numerical ratings do not always fully reflect the aspects expressed in written reviews. Certain factors influencing consumer satisfaction may be present in the text but are not captured by rating values alone.

Overall, this study highlights the importance of analysing both ratings and textual data to gain a more complete understanding of consumer opinions, particularly in the context of health-related products.

Future research could extend this analysis by examining a larger set of reviews to further explore the relationship between numerical ratings and textual sentiment. Such work may help to better understand cases where written feedback provides additional insight beyond rating values alone.


## Tools & Technologies
 - R (text mining, sentiment analysis, topic modeling)
 - NLP libraries for preprocessing and analysis
 - Statistical methods for exploratory analysis




