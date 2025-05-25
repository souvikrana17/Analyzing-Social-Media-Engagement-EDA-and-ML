# 📊 Analyzing Social Media Engagement: EDA and ML

This project analyzes social media post performance using a comprehensive dataset containing metadata and engagement metrics. The aim is to identify which features — such as sentiment, time, hashtags, and content — influence user engagement, and to build a machine learning model to predict future engagement rates.

---

## 🧠 Project Objective

To explore, visualize, and model how various features like sentiment, timing, and content impact **engagement rate** on social media platforms. We leverage regression analysis to predict engagement and extract meaningful insights for content optimization.

---

## 📁 Dataset Overview

The dataset includes the following key columns:

| Feature                  | Description |
|--------------------------|-------------|
| `post_id`               | Unique post identifier |
| `timestamp`, `hour`, `day_of_week` | Posting time and date |
| `platform`              | Social media platform |
| `user_id`, `location`, `language` | User demographics |
| `text_content`, `hashtags`, `mentions`, `keywords` | Post content details |
| `topic_category`        | Thematic tag of post |
| `sentiment_score`, `sentiment_label` | NLP-based sentiment analysis |
| `emotion_type`, `toxicity_score` | Emotion & toxicity markers |
| `likes_count`, `shares_count`, `comments_count`, `impressions` | Engagement metrics |
| `engagement_rate`       | Derived metric = (likes + shares + comments) / impressions |
| `brand_name`, `product_name`, `campaign_name`, `campaign_phase` | Marketing metadata |
| `user_past_sentiment_avg`, `user_engagement_growth`, `buzz_change_rate` | Historical user behavior |

---

## 📊 Exploratory Data Analysis (EDA)

Visualizations created to identify trends and relationships:

- 📈 **Engagement Rate by Hour of Day**: Boxplot showing peak times.
- 📆 **Weekday vs Weekend**: Analyzing how timing affects engagement.
- 📝 **Distribution of Text Length**: Effect of content size on interaction.
- 🔣 **Hashtag Count vs Engagement**: Visualizing impact of hashtags.
- ❤️‍🔥 **Sentiment × Toxicity vs Engagement**: Sentiment correlation.
- 🔠 **Word Count vs Engagement**: Simple textual complexity check.

---

## 🧮 Model Building

### ✅ Target Variable:
- `engagement_rate`

### 🧠 Features Used:
- `hour`, `day_of_week`
- `sentiment_score`, `toxicity_score`
- `text_length`, `word_count`, `hashtag_count`, `mention_count`
- `buzz_change_rate`, `user_engagement_growth`

### 🧪 Model Used:
- **Linear Regression**

### 📈 Model Performance:
- **Mean Squared Error (MSE):** `0.0173`
- **R² Score:** `0.986` (Very high accuracy)

---

## 📌 Key Insights

- **Best posting hours**: Engagement peaks during mid-day and late evenings.
- **Weekend engagement** is marginally lower than weekdays.
- **Positive sentiment** and **low toxicity** drive higher engagement.
- Excessive use of hashtags or mentions does not guarantee better engagement.
- Users with improving past engagement tend to receive more current attention.

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn for modeling
- Jupyter Notebook / Google Colab
- Kaggle for hosting analysis

---

## 🔗 Project Links

- 📓 [View the Kaggle Notebook]([https://www.kaggle.com/yourusername/your-notebook-name](https://www.kaggle.com/code/souvikrana17/analyzing-social-media-engagement-eda-and-ml))
- 📁 [Download the Dataset]([https://www.kaggle.com/yourdatasetlink](https://www.kaggle.com/datasets/subashmaster0411/social-media-engagement-dataset/data))

---

## 📌 Future Improvements

- Integrate deep learning (e.g., LSTM) for text-based engagement prediction
- Include more platforms (YouTube, LinkedIn) for a wider dataset
- Use advanced NLP features like BERT embeddings for text analysis
- Implement classification models for binary engagement classification (High vs Low)

---

## 🤝 Contributions

Feel free to fork the repo, explore the notebook, and submit pull requests with improvements, additional visualizations, or alternate models.

---


## 👋 Let's Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/souvik-rana-sr17/)
- 🧠 [Kaggle](https://www.kaggle.com/souvikrana17)
- 💻 [Portfolio](https://souvik-rana.vercel.app/)

---

