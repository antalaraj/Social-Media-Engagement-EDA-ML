# 📊 Social Media Engagement Analysis & Prediction (EDA + Machine Learning)

## 📌 Project Overview

This project analyzes social media engagement data using Exploratory Data Analysis (EDA) and Machine Learning to identify key factors influencing engagement rate and build a predictive model.

The project performs end-to-end data science workflow including:

* Data cleaning and preprocessing
* Feature engineering
* Exploratory Data Analysis (EDA)
* Machine Learning model development
* Model optimization and evaluation
* Feature importance analysis

The final model achieves **high predictive accuracy (R² = 0.978)**, demonstrating strong capability in predicting engagement rate.

---

## 🎯 Business Objective

The goal is to answer key business questions such as:

* Which content types generate the highest engagement?
* Which platforms perform best?
* Does posting time affect engagement?
* Do paid promotions improve engagement quality?
* What factors most strongly influence engagement rate?
* Can engagement rate be predicted using machine learning?

This helps optimize:

* Content strategy
* Posting schedule
* Platform selection
* Marketing performance

---

## 📂 Project Structure

```
Social-Media-Engagement-Analysis/
│
├── Code.ipynb
├── Social Media Engagement Dataset.csv
├── README.md
```

---

## 📊 Dataset Information

* Total records: **12,000 social media posts**
* Features include:

### Content Features

* topic_category
* hashtags
* caption_length
* mentions_count

### Platform Features

* platform
* campaign_phase

### Engagement Metrics

* impressions
* likes_count
* shares_count
* comments_count

### User Behavior Features

* user_post_frequency
* user_engagement_growth
* user_past_sentiment_avg

### Sentiment Features

* sentiment_score
* toxicity_score
* sentiment_label

### Time Features

* hour
* is_weekend

### Target Variable

* engagement_rate

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was performed to understand engagement patterns and relationships between features.

### Key Analysis Performed

* Data cleaning and preprocessing
* Missing value handling
* Feature engineering
* Distribution analysis
* Correlation analysis
* Platform comparison
* Content performance analysis
* Promotion effectiveness analysis

---

## 📈 Key Insights

### Content Performance

* Product, Delivery, and Support content show highest engagement
* Marketing and Pricing content show lower engagement

### Platform Performance

* Instagram and Facebook have highest engagement
* YouTube has slightly lower engagement

### Posting Time Impact

* Evening and Night posts perform better
* Afternoon posts perform worst

### Promotion Analysis

* Organic posts outperform paid posts
* Paid promotion does not guarantee higher engagement quality

### Sentiment Analysis

* Negative sentiment receives highest engagement
* Positive sentiment receives slightly lower engagement

### Engagement vs Followers

* Engagement rate decreases as impressions increase
* Larger accounts have lower engagement percentage

---

## 🤖 Machine Learning Model

### Model Used

Random Forest Regressor

Reason for selection:

* Handles nonlinear relationships
* Robust against overfitting
* Works well with mixed feature types
* Provides feature importance

---

## ⚙️ ML Pipeline Architecture

```
Data → Preprocessing → Feature Engineering → Encoding → Model Training → Evaluation → Feature Importance
```

Pipeline includes:

* ColumnTransformer
* OneHotEncoder
* RandomForestRegressor
* Hyperparameter tuning

---

## 🧠 Features Used in Model

```
topic_category
platform
campaign_phase
hashtag_count
caption_length
mentions_count
impressions
sentiment_score
toxicity_score
hour
likes_count
shares_count
comments_count
user_past_sentiment_avg
user_engagement_growth
buzz_change_rate
user_post_frequency
is_weekend
```

---

## 📊 Model Performance

Final optimized Random Forest Model:

```
R² Score: 0.9780
MAE:      0.0153
RMSE:     0.0618
```

### Interpretation

* Model explains **97.8% variance**
* Very low prediction error
* Excellent generalization
* Industry-level performance

---

## 📌 Feature Importance (Top Predictors)

Most important features:

1. impressions
2. likes_count
3. shares_count
4. comments_count
5. sentiment_score
6. toxicity_score
7. posting hour

These features strongly influence engagement rate.

---

## 🛠️ Tech Stack

Programming Language:

* Python

Libraries:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

Environment:

* Jupyter Notebook

---

## ▶️ How to Run

### Step 1: Clone repository

```bash
git clone https://github.com/yourusername/social-media-engagement-analysis.git
```

### Step 2: Open notebook

```bash
cd social-media-engagement-analysis
jupyter notebook
```

### Step 3: Run notebook

Open:

```
Code.ipynb
```

Run all cells sequentially.

---

## 🎓 Skills Demonstrated

This project demonstrates:

* Exploratory Data Analysis
* Data Cleaning
* Feature Engineering
* Machine Learning
* Model Optimization
* Model Evaluation
* Pipeline Architecture
* Feature Importance Analysis
* End-to-End ML workflow

---

## 💼 Real-World Applications

This model can be used for:

* Social media strategy optimization
* Marketing performance prediction
* Content performance prediction
* Influencer analytics
* Campaign optimization

---

## 👨‍💻 Author
Raj Antala  
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj

Passionate about building intelligent systems and real-world AI applications.

---

## ⭐ Conclusion

This project successfully demonstrates how data analysis and machine learning can be used to understand and predict social media engagement.

The optimized Random Forest model achieved excellent performance and identified key factors driving engagement, making this a strong real-world machine learning project suitable for production-level applications.

---


to make it look like a **top-tier data science portfolio project.**
