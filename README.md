#  YouTube Text Data Analysis with Python

This project dives deep into YouTube data to extract meaningful **insights from comments, titles, tags, and video metadata** using Python. It combines sentiment analysis, emoji trends, category-based analytics, and viewer engagement metrics — all in one interactive Jupyter Notebook.



##  Project Overview

With over 700,000 comments and 375,000+ video records analyzed, this project explores:

-  Sentiment behind viewer comments
-  Most-used emojis and their emotional tone
-  Popular categories based on likes and trends
-  Viewer engagement: likes, dislikes, comment rates
-  Correlation between punctuation in titles/tags and video performance
-  Trends in top-performing channels



##  Tech Stack

- **Languages**: Python 3
- **Libraries**: 
  - `pandas`, `numpy` – Data wrangling
  - `matplotlib`, `seaborn`, `plotly` – Visualization
  - `TextBlob` – Sentiment analysis
  - `emoji`, `wordcloud` – Text + Emoji analytics
  - `SQLAlchemy`, `SQLite` – Data export



##  Features & Modules

| Module | Description |
|--------|-------------|
| **1. Load Data** | Import YouTube comment and video metadata CSVs |
| **2. Sentiment Analysis** | Classify comments using TextBlob polarity |
| **3. Word Cloud** | Generate visuals for positive/negative words |
| **4. Emoji Analysis** | Identify most frequently used emojis |
| **5. Full Dataset Merge** | Combine metadata from multiple regional files |
| **6. Export Data** | Save as CSV, JSON, and SQLite |
| **7. Category Likes** | Find which categories drive most engagement |
| **8. Engagement Metrics** | Calculate like rate, dislike rate, comment rate |
| **9. Trending Channels** | Identify channels with most trending content |
| **10. Title Punctuation Analysis** | Analyze if punctuation affects views/likes |

##  Business Insight
1. Audience Sentiment & Engagement
* Insight: The majority of viewer comments carry neutral to positive sentiment, often using emojis like 😂, ❤️, and 🔥.
* Business Value: Indicates high audience satisfaction and emotional engagement. Creators and marketers can reinforce the emotional tone used in popular videos to boost engagement.

 2. Content Category Performance
* Insight: Entertainment and Music consistently receive the highest likes and engagement rates.
* Business Value: Brands and advertisers can prioritize these categories for influencer partnerships, ad placements, or branded content to maximize reach.

 3. Emoji & Word Usage Patterns
* Insight: Frequent use of emojis correlates with viewer enthusiasm, especially in positive sentiment clusters.
* Business Value: Social media teams can incorporate emotional visual language (emojis) in video titles, thumbnails, and descriptions to attract viewer attention.

 4. Engagement Metrics Reveal Viewer Behavior
* Insight: Higher like_rate and comment_rate are strongly correlated with higher views. Some categories (like Comedy and How-To) have higher viewer interaction rates.
* Business Value: These categories may be more suited for community building, user feedback, and product tutorials.

 5. Channel Benchmarking
* Insight: Channels like The Late Show and WWE dominate trending charts, suggesting content strategies worth replicating.
* Business Value: New content creators or brands can analyze top-performing channels to reverse-engineer upload frequency, style, and audience tone.

 6. Clickbait Doesn't Always Work
* Insight: Title punctuation or excessive formatting doesn’t show a consistent correlation with higher views or likes.
* Business Value: Focus should be on content quality and relevance rather than just catchy formatting — useful for SEO and copywriting strategies.
