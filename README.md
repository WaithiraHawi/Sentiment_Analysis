# Sentiment_Analysis

This dataset contains **40,000 tweets** with 4 columns:

* **tweet\_id**: Unique identifier for each tweet
* **sentiment**: The sentiment label (e.g., Positive, Negative, Neutral)
* **author**: The account that posted the tweet
* **content**: The tweet text

<img width="1024" height="1536" alt="Sentiment Analysis" src="https://github.com/user-attachments/assets/d0029b3f-3fbd-4f20-85f5-21aca99de133" />


### Sentiment Distribution

* Tweets were categorized into different sentiments.
* The **majority sentiment** shows the prevailing mood in the dataset.
* Visualization: A bar chart was generated to show which sentiment dominates. This helps understand the **overall emotional tone** in the dataset.
* It will identify whether community reaction is largely positive, negative, or neutral.

### Top Authors and Tweet Activity
The top 10 most active authors were identified.
Some users are highly active contributors, accounting for a significant portion of tweets.
This information is ideal for influencer detection in social media analytics, and filtering spam or bots if one user dominates the conversation

### Text Analysis

Tweet Length Distribution: 
The Tweets varied in length, with most being short-form (\~50–100 characters).
Short tweets are often reactions, while longer tweets may contain explanations or opinions.

Frequent Words
Common words in the dataset indicate the main topics of discussion.
After cleaning text (removing links, hashtags, and punctuation), the top 20 and top 30 frequent words were identified.
Findings: Words often reflect trending topics or common expressions tied to the dataset’s theme.

#### Top Bigrams
The Bigrams (2-word phrases)include "thank you", "good morning", or topic-specific phrases were identified.
Bigrams capture contextual meaning that single words may miss.

### Advanced Insights

Top Keywords per Sentiment
Each sentiment category has its own signature words:
* Positive:Words like great, love, happy dominate
* Negative:Words like bad, hate, sad dominate
* Neutral: Words often include factual or descriptive terms without emotion

Keyword Trends
By analyzing bigrams and frequent words per sentiment:
 Positive tweets cluster around appreciation or support.
 Negative tweets cluster around complaints or dissatisfaction.
 Neutral tweets often carry factual information or non-opinion statements.
 
## Conclusion 
The sentiment breakdown shows the overall mood of the dataset.

A few authors dominate tweet activity, possibly influencing sentiment trends.

Most tweets are short, consistent with typical social media usage.

Frequent words and bigrams reveal trending topics and emotional triggers.

Top keywords per sentiment enable targeted sentiment tracking and reporting.
