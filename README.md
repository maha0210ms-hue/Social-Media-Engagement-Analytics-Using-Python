## Social Media Engagement Analytics Using Python

### Project Overview

This project analyzes social media engagement data to uncover patterns in user interaction such as likes, comments, shares, impressions, watch time, and engagement rate. The goal is to identify what type of content performs best and derive actionable insights using Python-based data analysis and visualization.

### Objectives

- Understand engagement patterns across different content types  
- Identify factors influencing high engagement rates  
- Perform exploratory data analysis (EDA)  
- Visualize trends and correlations in the dataset  
- Generate business insights for content optimization  

### Dataset Description
The dataset contains 5000 records with 19 columns:
- user_id, age, gender, country  
- post_id, post_type, post_category  
- likes, comments, shares  
- watch_time_sec, impression_count  
- posted_at, follower_count  
- is_verified, device_type  
- sentiment, hashtags  
- engagement_rate  

### Data Cleaning & Preprocessing
- Handled missing values using median and mode  
- Removed duplicate records  
- Converted data types (datetime, integer, categorical)  
- Standardized text columns  
- Created new features:
  - engagement_score = likes + comments + shares  
  - hashtag_count  

### Exploratory Data Analysis (EDA)
- Distribution analysis of likes, comments, shares  
- Engagement rate by post type and category  
- Time-based trend analysis  
- Correlation analysis of numerical features  
- Groupby analysis for country, sentiment, and device type  

### Visualizations Used
- Scatter plots (likes vs impressions)  
- Line charts (daily engagement trend)  
- Bar charts (category and post type analysis)  
- Pie charts (gender distribution)  
- Histogram (age distribution)  
- Box plots (outlier detection)  
- Heatmaps (correlation analysis)  
- Violin & swarm plots  
- Interactive Plotly charts  

### Key Insights
- Image posts have the highest engagement rate  
- Music and Tech categories perform best  
- Germany and Australia show highest engagement rates  
- Mobile users have highest watch time  
- Non-verified users show higher engagement than verified users  
- Negative sentiment posts generate highest engagement  
- Tuesday and weekends have higher impressions  

### Final Conclusion

Engagement is influenced by multiple factors such as content type, sentiment, device usage, posting time, and user behavior. Emotionally engaging content and mobile-first consumption strongly drive higher interaction. This analysis helps optimize content strategy for better reach and engagement.

### Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- Jupyter Notebook  

### How to Run

```bash
git clone https://github.com/your-username/social-media-analytics.git
cd social-media-analytics
pip install -r requirements.txt
jupyter notebook
