# 📊 EDA-YouTube Usage Data Analysist-(Python)

## 📌 Project Overview
A complete Exploratory Data Analysis (EDA) and Sentiment Analysis project on YouTube trending videos and user comments using Python.
This project focuses on understanding audience engagement, user sentiment, emoji usage, trending categories, and channel performance through data visualization and NLP techniques.

The analysis includes data cleaning, preprocessing, visualization, and extracting insights using Python libraries like Numpy, pandas, Matplotlib.
<img width="750" height="360" alt="9074555_1591250182_youtube" src="https://github.com/user-attachments/assets/fd986bef-d953-4204-b9d1-ef92aeef667a" />


---

## 🚀 Project Overview
### This project analyzes YouTube trending video data and comments to uncover insights such as:

Sentiment of user comments
Most used emojis in comments
Trending video categories
Audience engagement metrics
Relationship between views, likes, and dislikes
Channels with the highest number of trending videos
Impact of punctuation in titles on engagement

### The project uses various Python libraries for:

Data Cleaning
Data Visualization
Natural Language Processing (NLP)
Statistical Analysis

---

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn


---

## 📂 Dataset Features
The dataset(UScomments) contains:
- Video id
- comment_text
- likes
- replies
  
The dataset (youtube_sample) contains:
- video_id
- trending_date
- title
- channel_title
- category_id
- publish_time
- tags
- views
- likes
- dislikes
- comment_count
- thumbnail_link
- comments_disabled
- ratings_disabled
- video_error_or_removed
- description

---


## 📊Steps and Workflow

### 🔹 Data Collection
Imported YouTube trending videos dataset
Loaded comments dataset and category metadata
Read data from CSV, JSON, and SQLite files

### 🔹 Data Understanding
- Explored dataset structure
Checked:
 - Data types
 - Missing values
 - Duplicate records
 - Statistical summary

### 🔹 Data Cleaning
- Removed null values and duplicates
- Converted columns into proper formats
- Filtered invalid or unnecessary data

### 🔹 Exploratory Data Analysis (EDA)
- Performed detailed analysis on:
  Views
  Likes
  Dislikes
  Comment counts
  Trending categories
  Channel performance

### 🔹 Sentiment Analysis
Used TextBlob for polarity analysis
Classified comments into:
 - Positive
 - Negative
 - Neutral

### 🔹 Emoji Analysis
 - Extracted emojis from comments
 - Calculated emoji frequencies
 - Visualized most commonly used emojis

### 🔹 Visualization
 - Heatmaps
 - Boxplots
 - Regression plots
 - Interactive charts
 - Word clouds

### 🔹Database Export
 - Stored processed data into SQLite database
 - Exported clean datasets for future use

## 📈 Key Findings and Insights
### Engagement Insights
 - Videos with higher views generally received higher likes
 - Strong positive correlation found between views and likes

### Sentiment Insights
 - Majority of comments were positive
 - Positive comments included words like: awesome great amazing
 - Negative comments frequently included: bad worst boring

### Trending Categories
 - Music and Entertainment categories dominated trending videos
 - These categories generated the highest audience interaction
   
### Emoji Usage
 - Positive emojis were used more frequently than negative emojis
 - Most common emojis reflected excitement and appreciation
   
### Channel Performance
 - Certain channels repeatedly appeared in trending sections
 - Popular creators maintained consistent engagement rates
   
### Title Analysis
 - Titles containing punctuation and emotional expressions often attracted more engagement

---

## 📁 Recommendations
### Improve Viewer Engagement
Use attractive and emotionally engaging video titles
Include relevant punctuation and keywords in titles

### Focus on Positive Audience Interaction
Encourage audience participation through comments and polls
Respond to user comments to increase engagement

### Content Strategy
Create more content around trending categories such as:
 - Music
 - Entertainment
 - Gaming

### Sentiment Monitoring
Track audience sentiment regularly to understand viewer preferences
Use sentiment analysis for content improvement

### Emoji & Comment Analysis
Analyze audience reactions using emojis and comments
Use audience feedback for future video planning

### Data-Driven Decisions
Use analytics to optimize:
 - Upload timing
 - Content type
 - Video titles
 - Thumbnail strategy

## 🏁 Conclusion
This project demonstrates how Data Analysis and Natural Language Processing (NLP) techniques can be used to extract valuable insights from YouTube data.

Through this analysis, we identified:
 - Audience behavior patterns
 - Sentiment trends
 - Popular content categories
 - Engagement relationships

The project highlights the importance of:
 - Data cleaning
 - Visualization
 - Sentiment analysis
 - Interactive analytics

Overall, this project provides meaningful insights that can help content creators and businesses make better, data-driven decisions to improve audience engagement and channel growth.
