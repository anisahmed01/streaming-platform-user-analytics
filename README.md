# 📊 Streaming Platform Analytics: Engagement, Retention, Conversion & Churn

## 📌 Overview
This project analyzes user behavior and subscription lifecycle data for a streaming platform to identify key drivers of engagement, retention, conversion, and churn.

The analysis focuses on understanding how user activity influences monetization and churn patterns, and provides actionable insights for improving user retention and business performance.

---

## 🎯 Business Problem
The platform faces challenges in:
- Converting active users into paying subscribers  
- Retaining users over time  
- Understanding behavioral patterns leading to churn  

---

## 🎯 Objective
To analyze user behavior and engagement patterns to uncover drivers of retention, conversion, and churn, and generate actionable insights to improve user retention and monetization.

---

## 🗂️ Dataset
The dataset consists of simulated streaming platform(Netflix)  data:

- **Users Table** – user demographics and acquisition details  
- **Events Table** – user actions (app usage, search, content viewing, etc.)  
- **Sessions Table** – aggregated user interaction sessions  
- **Subscriptions Table** – subscription lifecycle (start, end, churn status)  
- **User Activity Table** – daily user behavior  

---

## ⚙️ Data Processing
- Handled missing and inconsistent values  
- Created derived tables:
  - Sessions (session-level aggregation)
  - Subscriptions (subscription lifecycle tracking)
  - User Activity (daily behavioral data)
- Defined meaningful engagement events:
  - app_open, search, play_content, add_to_watchlist, onboarding  

---

## 📊 Key Insights

### 1. Content Consumption Drives Conversion
Users who consume content are **5–6x more likely to subscribe**, making engagement the strongest monetization driver.

---

### 2. Early Activity Drives Retention
Users with higher activity in early stages are **~5x more likely to retain**, highlighting the importance of habit formation.

---

### 3. Engagement is Higher Among Subscribers
Subscribed users show **~40% higher content consumption per active day**, indicating stronger value realization.

---

### 4. Engagement Declines Before Churn
User engagement drops by **~60% in the 7 days before churn**, making it a strong leading indicator for churn prediction.

---

### 5. Churn is a Terminal Event
Only **~5% of churned users remain active**, indicating that post-churn recovery opportunities are limited.

---

### 6. Platform Has No Significant Impact
No meaningful difference in engagement or conversion across Android, iOS, and Web platforms.

---

## 💡 Business Recommendations

- **Early Churn Detection**  
  Monitor declining engagement to identify at-risk users  

- **Improve Content Discovery**  
  Encourage early content consumption to drive conversion  

- **Target Active Non-Subscribers**  
  Use personalized nudges and offers  

- **Focus on Engagement Growth**  
  Enhance onboarding and content experience  

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy)  
- Jupyter Notebook / Google Colab  
- Data Analysis & Visualization  

---

## 📁 Project Structure
```
├── data (users.csv & events.csv)
├── analysis.ipynb
├── presentation.pptx
├── Dashboard Images
├── README.md
```
---


---

## 🚀 Key Takeaway
User engagement is the central driver of retention, conversion, and churn. A significant decline in engagement precedes churn, emphasizing the importance of early intervention rather than post-churn recovery.

---

## 👤 Author
**Anis Ahmed**  
