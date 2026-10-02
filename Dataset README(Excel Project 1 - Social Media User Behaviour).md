# 📱 Social Media User Behavior Dataset

**Author:** Hamna Munir  
**Version:** 1.0.0  
**Last Updated:** April 2026  
**License:** CC BY 4.0  
**Dataset Type:** Synthetic / Simulated  

---

## 📌 Overview

This dataset provides a comprehensive, synthetic snapshot of **social media user behavior** across major platforms including Instagram, TikTok, Twitter/X, Facebook, YouTube, Snapchat, LinkedIn, and Pinterest. It is designed for researchers, data scientists, and students interested in exploring patterns in digital behavior, platform engagement, mental health correlations, and e-commerce interactions driven by social media.

The data was synthetically generated using statistically realistic distributions and is **not sourced from any real individuals**. It is fully anonymized and safe for research, academic, and machine learning use.

---

## 🎯 Use Cases

- **Exploratory Data Analysis (EDA)** of social media usage patterns
- **Behavioral segmentation** and user clustering (K-Means, DBSCAN)
- **Mental health vs. screen time** correlation studies
- **Influencer identification** based on follower count and engagement
- **Social commerce** analysis (ad click rates, purchase behavior)
- **Platform preference modeling** and recommendation systems
- **Time-series analysis** of account age vs. engagement
- **Classification tasks**: predict influencer status, purchase behavior, screen time concern

---

## 📁 Files

| File | Description |
|------|-------------|
| `social_media_user_behavior.csv` | Main dataset — 2,000 rows × 34 columns |
| `README.md` | This file — full documentation |

---

## 📊 Dataset Schema

### 🔑 Identifier

| Column | Type | Description |
|--------|------|-------------|
| `user_id` | string | Unique user identifier (e.g., USR00001) |

---

### 👤 Demographics

| Column | Type | Description | Sample Values |
|--------|------|-------------|---------------|
| `age` | int | User age | 13–65 |
| `gender` | string | Gender identity | Male, Female, Non-binary, Prefer not to say |
| `country` | string | Country of residence | Pakistan, India, USA, UK, UAE, Canada, Germany, Australia, Brazil, Nigeria |
| `profession` | string | Occupation | Student, Engineer, Designer, Teacher, Freelancer, Doctor, Marketer, Entrepreneur, Researcher, Other |

---

### 📱 Platform & Device Usage

| Column | Type | Description | Sample Values |
|--------|------|-------------|---------------|
| `primary_platform` | string | Most used social media platform | Instagram, TikTok, Twitter/X, Facebook, YouTube, Snapchat, LinkedIn, Pinterest |
| `platforms_used_count` | int | Total number of platforms actively used | 1–5 |
| `preferred_device` | string | Main device for social media | Smartphone, Laptop, Tablet, Desktop, Smart TV |
| `peak_usage_time` | string | Time of day with highest usage | Morning, Afternoon, Evening, Night, Late Night |
| `account_join_date` | date | Date user joined their primary platform | 2022-01-01 to 2024-12-31 |

---

### ⏱️ Time & Session Metrics

| Column | Type | Description |
|--------|------|-------------|
| `daily_usage_hours` | float | Average hours spent on social media per day |
| `sessions_per_day` | int | Number of separate sessions opened per day |
| `avg_session_duration_min` | float | Average duration of one session in minutes |

---

### 📣 Engagement Metrics

| Column | Type | Description |
|--------|------|-------------|
| `followers_count` | int | Number of followers on primary platform |
| `following_count` | int | Number of accounts followed |
| `posts_per_week` | int | Average posts published per week |
| `likes_given_per_day` | int | Number of likes/reactions given per day |
| `comments_per_day` | int | Number of comments posted per day |
| `shares_per_day` | int | Number of posts shared/reposted per day |
| `dms_sent_per_day` | int | Direct messages sent per day |
| `preferred_content_type` | string | Type of content most consumed | Videos, Reels/Shorts, Photos, Stories, Memes, News, Educational, Entertainment |
| `scroll_speed` | string | Typical scrolling behavior | Slow, Medium, Fast |
| `influencer_status` | string | Whether user has >10K followers | Yes, No |

---

### 🛒 Social Commerce

| Column | Type | Description |
|--------|------|-------------|
| `ad_click_rate` | float | Proportion of ads clicked (0.0–1.0) |
| `purchased_via_social_media` | string | Has user bought products via social media? | Yes, No, Sometimes |
| `monthly_spend_via_social_usd` | float | Estimated monthly purchase amount via social (USD) |
| `primary_purpose` | string | Main reason for using social media | Entertainment, Networking, News & Updates, Business/Marketing, Learning, Socializing |

---

### 🧠 Mental Health & Well-being

| Column | Type | Description | Scale |
|--------|------|-------------|-------|
| `sleep_disruption` | string | Impact of social media on sleep | No impact → Severe impact |
| `self_reported_mental_health_score` | float | User's self-rated mental health | 1 (Very Poor) – 10 (Excellent) |
| `screen_time_concern` | string | Is user concerned about screen time? | Yes, No, Somewhat |
| `mood_while_scrolling` | string | Typical mood reported while browsing | Happy, Neutral, Stressed, Relaxed, Bored, Inspired |
| `takes_social_media_breaks` | string | Does user take deliberate digital breaks? | Yes, No, Occasionally |

---

### 🔒 Privacy & Notifications

| Column | Type | Description |
|--------|------|-------------|
| `notification_frequency` | string | Notification settings | Always On, Selected, Do Not Disturb, Off |
| `privacy_setting` | string | Profile visibility setting | Public, Friends Only, Private |

---

## 📈 Key Statistics

| Metric | Value |
|--------|-------|
| Total Records | 2,000 |
| Total Features | 34 |
| Age Range | 13 – 65 years |
| Mean Age | ~27 years |
| Mean Daily Usage | ~3 hours |
| Max Followers | ~5,000,000 |
| Influencer Rate | ~12% |

---

## 🔬 Suggested Research Questions

1. Does higher daily social media usage correlate with lower mental health scores?
2. Which platform is associated with the highest engagement rates?
3. Can we predict whether a user will make a social media purchase based on their behavior?
4. How does age group affect platform preference and usage duration?
5. Is there a relationship between notification settings and screen time concern?
6. Do users with more followers report different moods while scrolling?
7. What behavioral traits distinguish influencers from regular users?

---

## ⚠️ Disclaimer

This dataset is **entirely synthetic**. All records were generated programmatically using randomized statistical distributions. No real user data was collected, scraped, or derived from any social media platform. Any resemblance to real individuals is coincidental. This dataset must **not** be used to make real-world claims about specific individuals, platforms, or demographics.

---

## 📜 Citation

If you use this dataset in your work, please cite it as:

```
Munir, H. (2026). Social Media User Behavior Dataset (Synthetic) [Data set]. Kaggle.
https://www.kaggle.com/datasets/hamnamunir/social-media-user-behavior
```

---

## 🤝 Author

**Hamna Munir**  
Data Scientist & Researcher  
📧 Available via Kaggle profile  
🌐 Kaggle: [kaggle.com/hamnamunir](https://www.kaggle.com/hamnamunir)

---

*Dataset generated for educational and research purposes. Distributed under CC BY 4.0 License.*
