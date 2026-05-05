# Brand Sentiment — Multi-Source Intelligence & Reputation Analytics Platform

---
<p align="center">
  <img src="assets/Brand_Sentiment_Tool.gif" width="900"/>
</p>
##  Overview

**Brand Sentiment** is a full-stack analytics platform designed to help organizations understand how their brand is perceived across the digital landscape.

It aggregates and analyzes data from multiple high-impact sources, including:

- Google Web results  
- Instagram  
- Facebook  
- Reddit  
- TikTok  

It delivers actionable insights on:

- Public perception  
- Customer sentiment  
- Competitive positioning  
- Marketing opportunities  

This project is built as a **scalable framework** that can be adapted for any company, in any industry.

> The included examples (e.g., cable TV and social media video services) are demonstration use cases only.

At its core, Brand Sentiment transforms fragmented online feedback into structured intelligence for better business decisions.

---

##  Why Brand Sentiment Matters

Modern companies receive thousands of opinions across digital platforms.

The challenge is not data collection — it is **understanding it quickly and meaningfully**.

This platform solves that by:

- Centralizing feedback from multiple platforms  
- Quantifying sentiment and emotional signals  
- Identifying recurring complaints and praise  
- Summarizing customer voice at scale  
- Enabling AI-assisted response strategies  
- Supporting competitive benchmarking  
- Automating reporting workflows  

👉 Turning raw feedback into a measurable business asset.

---

##  Key Features

### 1. Home

A visually engaging landing page introducing the platform’s purpose and capabilities.

---

### 2. Dashboard (Core Engine)

The analytical heart of the platform.

Users configure:
- Date range
- AI credentials

#### 📊 Data Views
- Overall (Web + Social Media)
- Web
- Social Media

#### 📈 Analytics Included
- Sentiment analysis  
- Confidence scoring  
- Emotion detection  
- Top emotional words  
- Top positive keywords  
- Top negative keywords  

#### 🎨 Visual Intelligence
- Brand association word clouds  
- Emoji engagement clouds  

---

### 🤖 AI Summary Engine

Automatically summarizes large volumes of feedback into key insights.

Instead of reading thousands of comments, users get:

- Key themes  
- Sentiment patterns  
- Emerging narratives  

---

### 🔍 “Let’s Sift Through the Comments” (PCA Analysis)

Uses **Principal Component Analysis (PCA)** to visualize negative feedback clusters.

#### Purpose:
- Detect recurring complaint patterns  
- Understand dissatisfaction relationships  
- Identify major issue clusters  
- Prioritize business problems  

👉 Converts qualitative feedback into measurable structure.

---

### 📂 Downloadable Dataset

- Export comments in CSV/Excel format  
- Supports offline analysis  
- Enables reporting & collaboration  

---

### 🧠 AI Response Strategy Agent

> “Concerns? Complaints? Criticism? AI’s Got the Next Move!”

Users select complaint categories and receive:

- AI-driven response strategies  
- Suggested actions for resolution  
- Communication recommendations  

👉 Moves from insight → action.

---

### 3. Reports Module

Fully customizable reporting system.

Users can:
- Select date ranges  
- Choose data sources  
- Select metrics  
- Generate downloadable reports  

---

### 4. Email Integration

Send insights directly from the platform.

Use cases:
- Share reports instantly  
- Team communication  
- Reduce platform switching  

---

### 5. Marketing Assistant

AI-powered content generation tool for:

- Cold emails  
- Ad copy  
- Social captions  
- SEO blog outlines  
- Product descriptions  
- Newsletters  
- Landing page headlines  

Supports **tone customization** for brand alignment.

---

### 6. Counterparts (Competitor Analysis)

Benchmark competitors using:

- Sentiment  
- Emotion analysis  
- Keyword trends  

#### Example Industries:
- Cable TV  
- Streaming services  

Also includes financial scraping (demo):

- Comcast (Q3 revenue, dividend data)  
- Netflix (Q3 revenue, dividend data)

👉 Expands into business intelligence beyond sentiment.

---

## 🔐 Technical Requirements

### In-App Credentials

Users must provide API credentials inside the app for full functionality.

---

### `.env` Setup

```env
# Google Scraping
API_KEY=your_google_api_key
CSE_ID=your_google_custom_search_engine_id

# Instagram
access_token=your_instagram_access_token
business_id=your_instagram_business_id

# Facebook
acct_t=your_facebook_access_token
page_id=your_facebook_page_id

# Reddit
client_id=your_reddit_client_id
client_secret=your_reddit_client_secret
user_agent=your_reddit_user_agent


Note: The source code for this project is hosted in a private repository to protect proprietary algorithms and data structures. For inquiries regarding the codebase, please contact the author.
