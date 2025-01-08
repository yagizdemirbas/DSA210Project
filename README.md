# **DSA210Project**  
**Forecasting and Thematic Analysis of Personal Twitter Activity**

---

## **Motivation**  
Twitter activity, such as liking, retweeting, and tweeting, reflects personal interests, engagement patterns, and evolving trends. Analyzing this data not only uncovers historical patterns but also enables predictions about future behaviors and preferences.  

This project aims to:  
- Analyze my historical Twitter activity to uncover patterns in engagement and content.  
- Develop models to forecast future tweet activity based on temporal trends.  
- Use thematic analysis to classify and predict the content types I engage with most.  

This analysis will help better understand my preferences, engagement habits, and future trends in my Twitter activity.

---

## **Main Research Questions**  

### **Engagement Trends**  
- How has my liking, retweeting, and tweeting activity evolved over time?  
- Are there specific periods of increased or decreased activity?  
- Can I predict future trends in my Twitter engagement (e.g., daily tweet counts)?  

### **Tweet Content and Themes**  
- What are the most common themes, topics, or hashtags in my tweets?  
- How do these themes change over time?  
- What is the sentiment of my tweets, and how does it evolve over time?  
- Can I classify tweets into distinct thematic categories using clustering?  

### **Time-Based Activity**  
- At what times or days am I most active on Twitter?  
- Is there a correlation between the time of activity and the themes or sentiment of my tweets?  

---

## **Data Source**  
The dataset for this project will be derived from my personal Twitter archive, which includes:  
- **Tweets**: My own tweets, including text, timestamps, and metadata (e.g., hashtags, mentions).  
- **Likes**: Details of tweets I’ve liked, including content, timestamp, and author.  
- **Retweets**: Information on tweets I’ve retweeted, including content and original author.  

This archive provides a comprehensive view of my activity on Twitter and serves as the foundation for analysis and modeling.

---

## **Project Goals**  

### **1. Engagement Analysis**  
- Explore historical trends in likes, retweets, and tweets to identify engagement patterns over time.  
- Develop metrics to measure activity and interaction frequency.  

### **2. Forecasting Trends**  
- Build time series models to forecast future tweet activity (e.g., daily tweet counts).  
- Identify seasonal or periodic patterns in my Twitter usage.  

### **3. Thematic and Content Insights**  
- Perform clustering and topic modeling to identify recurring themes in my tweets.  
- Analyze how themes correlate with engagement and sentiment.  

### **4. Sentiment Analysis**  
- Assess the sentiment (positive, negative, neutral) of my tweets and analyze its evolution over time.  
- Identify the relationship between sentiment and thematic trends.  

### **5. Visualizing Patterns**  
- Develop visualizations to highlight temporal trends, engagement statistics, and thematic clusters.  

### **6. Future Activity Predictions**  
- Combine thematic analysis and time series forecasting to predict future activity patterns and themes.  

---

## **Methodology**  

### **1. Data Preprocessing**  
- Extract data from my Twitter archive.  
- Clean and structure data, ensuring fields like timestamps, content, and metadata are ready for analysis.  
- Categorize data into tweets, likes, and retweets for targeted analysis.  

### **2. Exploratory Data Analysis (EDA)**  
- Analyze daily and hourly trends in engagement.  
- Generate summary statistics and identify outliers or spikes in activity.  
- Visualize activity trends over time.  

### **3. Text and Thematic Analysis**  
- Perform text preprocessing (e.g., tokenization, stopword removal, and stemming).  
- Use clustering and topic modeling (e.g., K-Means, LDA) to uncover key themes in tweets.  
- Analyze the distribution of themes and their temporal changes.  

### **4. Sentiment Analysis**  
- Apply sentiment analysis to tweets to classify them as positive, negative, or neutral.  
- Track sentiment over time to detect patterns and trends.  

### **5. Forecasting with Time Series Models**  
- Use ARIMA or advanced models (e.g., Prophet, LSTM) to forecast future activity.  
- Predict daily or hourly tweet counts for the next 7–30 days.  
- Evaluate model performance using metrics like RMSE or MAE.  

### **6. Insights and Recommendations**  
- Reflect on the analysis and modeling results to understand how my activity aligns with personal interests.  
- Provide actionable insights for optimizing future engagement or content strategy.  

---

## **Expected Deliverables**  

1. **Analytical Insights:**  
   - Trends in engagement patterns (likes, retweets, and tweets).  
   - Themes and topics of interest based on clustering and topic modeling.  
   - Sentiment evolution over time.  

2. **Forecasting Model:**  
   - A predictive model for daily tweet counts and activity trends.  
   - Visualizations of forecasted activity and patterns.  

3. **Visual Representations:**  
   - Time-based activity charts (daily, hourly).  
   - Word clouds and thematic visualizations.  
   - Forecasting graphs showing observed and predicted trends.  

4. **Recommendations:**  
   - Suggestions for content themes and timing to optimize engagement.  
   - Insights on how my Twitter activity aligns with personal interests and habits.  
