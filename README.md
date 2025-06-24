Overview
This tool is an AI-powered news monitoring dashboard built to track sentiment, earnings, and product-related news for key automotive accounts in the Americas. It runs daily in a Google Colab virtual machine, scrapes the latest headlines using RSS and GNews, analyzes sentiment with VADER, summarizes articles using Hugging Face's transformer model, and visualizes insights in a clean HTML dashboard hosted on GitHub Pages — all at zero cost. The tool highlights trending companies, tracks key product keywords (e.g. Android Auto, Snapdragon), and archives both HTML and CSV logs to monitor shifts in market perception over time.

 

How does it use AI 
🧠 Generative AI (GenAI)
Feature

Description

AI-Powered Summarization

Uses Hugging Face's facebook/bart-large-cnn transformer to auto-summarize articles — this is true GenAI (text generation).

Natural Language Output

Creates human-readable summaries and dashboard content from raw data — turning data into narrative.

Auto-generated Web Dashboard

Daily HTML page is dynamically written and styled with summaries, sentiment scores, and links, making the insight delivery.

📊 Machine Learning / NLP
Feature

Description

Sentiment Analysis

Uses VADER to analyze sentiment scores of news headlines and article bodies.

Keyword Matching (Priority Scoring)

Custom keyword engine tags articles relevant to in-vehicle tech, infotainment, ADAS, etc. — semi-ML/NLP logic.

Trend Tracking

Calculates average sentiment per company, revenue growth from Yahoo Finance, and earnings dates — creates a light predictive picture.

Daily Automation & Logging

Automatically pulls, filters, logs and updates CSV/HTML files — this is automation with data intelligence.

High Level Design 

image-20250514-192017.png
 

call me hand Help Needed 

Migrate code from Colab virtual machine and run in TT environment 

Replace facebook/bart-large-cnn with OpenAI 

Replace GoogleDrive with TT Sharepoint- OneDrive 

 

package Upcoming 

Moving averages for sentiment scoring and automated alerts

Add social media verbatims for each OEM ( Facebook - Twitter X - Reddit ) 

Weekly and Monthly Automated Summary 


