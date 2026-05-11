# YouStat – Advanced YouTube Analytics & Machine Learning Platform

YouStat is a data-driven YouTube analytics and machine learning system built with Python and Streamlit. It uses the YouTube Data API (Google Cloud) to extract channel data and applies statistical analysis, feature engineering, and machine learning models to generate insights and predictions.

Live Demo: *(add your own link here)*

---

## Project Overview

This project analyzes YouTube channel performance at a deep analytical level. It combines descriptive statistics, probability modeling, and machine learning techniques to understand historical behavior and predict future video performance.

The system is designed for:
- Channel growth analysis
- Content performance evaluation
- Predictive modeling of video views
- Business intelligence insights for creators

---

## Key Features

### YouTube Data Analytics
- Video-level and channel-level performance metrics
- Views, likes, comments, and engagement rate analysis
- Upload frequency and publishing pattern analysis
- Time-based trends (hour, day, month, quarter)

### Feature Engineering
- Rolling averages (5, 10, 20 videos) for momentum tracking
- Upload gap analysis (days between uploads)
- Title-based features (length, word count)
- Temporal encoding (weekday, hour, seasonality)
- Channel progression indexing

### Machine Learning Models
- Linear Regression for long-term growth trends
- Random Forest Regressor for performance prediction
- Log-transformed modeling for stability
- Future performance forecasting (next uploads)

### Statistical Analysis
- Descriptive statistics (mean, median, variance, skewness, kurtosis)
- Confidence intervals for key metrics
- Probability distribution fitting (Normal and Poisson)
- Z-score based viral content detection

### Business Intelligence
- Revenue estimation using RPM-based model
- Channel health scoring system
- Video categorization (Viral, Hit, Above Average, Average, Flop)
- Growth metrics (weekly, monthly, yearly trends)
- Best time and day to upload analysis

### Anomaly Detection
- IQR-based outlier detection
- Viral video identification
- Performance deviation analysis

---

## Tech Stack

- Python
- Streamlit
- Pandas, NumPy
- Scikit-learn
- SciPy
- YouTube Data API v3 (Google Cloud)

---

## Machine Learning Methodology

### Models Used
- Linear Regression (trend modeling)
- Random Forest Regressor (non-linear prediction)

### Feature Set Includes
- Video metadata (duration, title, publish time)
- Engagement metrics
- Rolling statistical features
- Temporal patterns
- Channel activity signals

### Evaluation Metrics
- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## Project Modules

- Data extraction from YouTube API
- Feature engineering pipeline
- Statistical analysis engine
- Machine learning prediction system
- Revenue estimation module
- Channel health scoring system

---

## Installation & Setup

```bash
git clone https://github.com/your-username/youstat.git
cd youstat
pip install -r requirements.txt
streamlit run app.py
```

---

## API Setup

This project requires YouTube Data API v3.

Steps:
1. Create a project in Google Cloud Console
2. Enable YouTube Data API v3
3. Generate an API key
4. Add the key to your project configuration

---

## Use Cases

- YouTube content creators analyzing channel growth
- Data science and machine learning portfolio project
- Video performance optimization
- Content strategy planning
- Revenue forecasting for creators

---

## Future Improvements

- Deep learning models for time-series forecasting (LSTM/GRU)
- AI-based content recommendation system
- Multi-channel comparative analytics
- Automated SEO and tagging suggestions
- Real-time streaming analytics dashboard

---

## Author

Developed by: Your Name  
Focus: Data Science, Machine Learning, Web Analytics

---

## Notes

This project demonstrates real-world application of machine learning and statistical analysis on YouTube data using API integration, feature engineering, and predictive modeling techniques.
