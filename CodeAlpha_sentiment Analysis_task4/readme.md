This project is part of Task 4: Sentiment Analysis for the CodeAlpha Data Analyst Internship.
The objective is to analyze Amazon Electronics reviews and classify them into positive, neutral, or negative sentiments using Natural Language Processing (NLP).
Two sentiment approaches were applied:
1.Rating-based sentiment (derived from star ratings)
2.Text-based sentiment using VADER
This helps understand customer satisfaction, opinion patterns, and product issues.

📂 Dataset
The dataset consists of Amazon electronics product reviews including:
Review text
Rating
Product title
Product price
Category
Product link
This is the same dataset used previously in Task 2 (EDA).

## Data Cleaning & Preprocessing
The following steps were performed to prepare the data:
1.Filled missing review texts
2.Converted text to lowercase
3.Removed punctuation and stopwords
4.Created a processed review column
5.Converted ratings into sentiment labels:
 Positive → 4–5 stars
 Neutral → 3 stars
 Negative → 1–2 stars
These steps ensure clean, structured data for sentiment modeling.

## Sentiment Analysis Using VADER

VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon-based NLP model optimized for short reviews.

VADER produces:
Positive score
Negative score
Neutral score
Compound score (final metric)
** Classification rule based on compound score:**
Positive → score ≥ 0.05
Neutral → -0.05 < score < 0.05
Negative → score ≤ -0.05
A new column vader_sentiment was created to store the predicted sentiment.

## Visualizations

The following visualizations were generated:
1.Rating Distribution
2.VADER Sentiment Distribution
3.Rating Sentiment vs VADER Sentiment Comparison
4.Top Word Frequencies for:
a.Positive reviews
b.Negative reviews
c.Neutral reviews
These help reveal customer opinion patterns and commonly used terms.

##  Model Evaluation

To evaluate VADER's performance:
1.Confusion Matrix (rating sentiment vs text sentiment)
2.Classification Report
3.Precision
4.Recall
5.F1 Score
This comparison helps assess how closely VADER aligns with real customer ratings.

 ## Key Insights
Most reviews are positive, indicating strong customer satisfaction.

1.**Common positive words:** great, excellent, love, perfect.
2.**Common negative words:** poor, broken, returned, disappointed.
3.**Neutral reviews** tend to include factual or mixed statements.
4.*VADER* matches rating sentiment well, especially for strong positive reviews.
5.*Mismatches*occur in short reviews or when the text sentiment doesn’t match the star rating.
Insights can support marketing, product improvements, and customer experience decisions.
## Ethical Considerations
Data used is publicly available Amazon review data.
No personal or sensitive information is included.
This project is for educational and internship evaluation purposes only.
📄 Files in This Folder
[CodeAlpha_SentimentAnalysis.ipynb](CodeAlpha_SentimentAnalysis.ipynb )
Task2_vedio link-
## Conclusion
This project demonstrates the complete sentiment analysis workflow using NLP, including preprocessing, sentiment scoring, visualizations, and evaluation.
It fulfills all required components of Task 4 for the CodeAlpha Data Analyst Internship.
