# Brand & Entity Sentiment Tracker on Social Media

An exploratory natural language processing (NLP) and data analysis project to identify, visualize, and track sentiment patterns towards major entities, brands, and games on Twitter.

## 📌 Project Overview
Social media is a major driver of public brand perception. This project processes Twitter feed records to analyze user sentiment patterns (positive, negative, neutral, irrelevant) targeted at major brands (e.g., Google, Microsoft) and entertainment franchises (e.g., Rainbow Six). By classifying and visualising sentiments, it provides an analytical look at public attitudes and brand engagement.

## 🚀 Key Features
* **Multi-Class Sentiment Profiling:** Analyzes user posts across four core categories: Positive, Negative, Neutral, and Irrelevant.
* **Entity-Level Dissection:** Tracks and ranks entities by discussion volume and maps sentiment splits specific to each entity.
* **Correlative Heatmaps:** Utilizes matrices to expose positive/negative sentiment biases towards different brands.
* **Custom NLP Visualizations:** Implements pie charts, topic-specific count plots, and frequency charts to summarize social dialogue.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Processing & Analytics:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn, WordCloud

## 📈 Methodology & Pipeline
1. **Data Acquisition:** Acquired a corpus of labeled entity-directed tweets from the [Kaggle Twitter Entity Sentiment Analysis Dataset](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis).
2. **Data Cleaning & Text Validation:**
   * Handled empty text fields and invalid data rows.
   * Standardized text inputs and structured entity tags.
3. **Exploratory Data Analysis (EDA):**
   * Computed global sentiment distribution ratios.
   * Grouped sentiments by brand entity to compare public sentiment trends.
4. **Data Visualization:**
   * Plotted global sentiment breakdowns as a pie chart.
   * Rendered topic-wise counts and topic-sentiment heatmaps for comparative analysis.

## 💡 Key Insights
* **High-Volume Entities:** Gaming entities (e.g., "TomClancyRainbowSix") generated the highest volume of social dialogue and showed highly polarized positive and negative distributions.
* **Corporate Brand Profiles:** Institutional tech entities like "Google" and "Microsoft" had predominantly neutral sentiments, indicating a dominance of objective news sharing and professional discussions.
* **Global Sentiment Balance:** While negative sentiment represented a notable share (~30.3%), positive and neutral components maintained a balanced division, showing diverse consumer opinions.

## 📂 Project Structure
```text
├── twitter_brand_sentiment_analyzer.ipynb # Sentiment analysis, plotting, and text EDA notebook
├── twitter_training.csv                   # Labeled social media training corpus
└── README.md                              # Project documentation
```

## 👤 Author
* **Khan Sohail**
  * [LinkedIn](https://www.linkedin.com/in/khan-sohail-386b2027a)
  * Email: ks646397@gmail.com
