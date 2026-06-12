# 📊 EDA-YouTube Usage Data Analysist-(Python)

## 📌 Project Overview
A complete Exploratory Data Analysis (EDA) and Sentiment Analysis project on YouTube trending videos and user comments using Python.
This project focuses on understanding audience engagement, user sentiment, emoji usage, trending categories, and channel performance through data visualization and NLP techniques.

The analysis includes data cleaning, preprocessing, visualization, and extracting insights using Python libraries like Numpy, pandas, Matplotlib.

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
---
### 🔹 Sentiment Analysis
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

## 📈 Key Insights
- Entertainment and Music categories receive high engagement.
- Strong correlation exists between views, likes, and comments.
- Trending videos show specific upload timing patterns.
- Higher engagement often leads to increased visibility.

---

## 📁 Project Structure

```bash
YouTube-Data-Analysis/
│
├── data/
├── notebooks/
├── images/
├── README.md
└── requirements.txt
