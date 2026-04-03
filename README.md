# App-Reviews-and-Sentiment-Analysisis
📌 Project Overview

This project performs sentiment analysis on user reviews of mobile applications from the Google Play Store using Natural Language Processing (NLP) techniques. The goal is to analyze user feedback and classify it into positive or negative sentiments.

🎯 Objectives

Collect user reviews from the Google Play Store
Analyze customer feedback using NLP
Classify sentiments into positive/negative categories
Visualize sentiment distribution across apps

🛠 Tech Stack

Python
Pandas & NumPy – Data processing

Google Play Scraper – Data collection

Hugging Face Transformers – Sentiment analysis

Plotly – Data visualization

📂 Dataset

Data is collected dynamically using:

google_play_scraper

Source: Multiple Apps from Google Play Store

Includes:

User reviews
Ratings

Timestamps

⚙️ Project Workflow

1️⃣ Data Collection

Extracted user reviews from different apps using Google Play Scraper

2️⃣ Data Preprocessing

Cleaned and structured text data
Converted review content into usable format

3️⃣ Sentiment Analysis

Used pre-trained transformer model:
siebert/sentiment-roberta-large-english
Classified reviews into:
Positive
Negative

4️⃣ Visualization

Created interactive plots using Plotly
Analyzed sentiment distribution across apps

📊 Results

Successfully analyzed user reviews from multiple applications
Identified overall sentiment trends
Provided insights into user satisfaction

📈 Output

Sentiment distribution charts
Dataset with sentiment labels

🚀 Key Features

Works for any app on Google Play Store
Real-time data extraction
NLP-based sentiment classification
Interactive visualization

💡 Future Improvements

Add neutral sentiment category
Compare sentiment across multiple apps
Build dashboard using Power BI / Streamlit
Deploy as a web application

🧠 Learnings

NLP and sentiment analysis using transformers
Handling real-world text data
Data visualization techniques
API-based data collection

⭐ Conclusion

This project demonstrates how sentiment analysis can be applied to user reviews from any Google Play Store app to extract meaningful insights and improve decision-making.
