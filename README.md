This project presents an Exploratory Data Analysis (EDA) of the Google Play Store dataset to understand the factors that influence app performance, popularity, and user satisfaction. The analysis was carried out using Python and focuses on identifying meaningful patterns in app ratings, installs, reviews, pricing, categories, and user sentiments. The project also incorporates a User Reviews dataset to analyze customer feedback using sentiment analysis, providing additional insights into user perceptions of different applications.

**Business Objective**

The primary objective of this project is to analyze Google Play Store applications and provide actionable insights that can help developers and businesses:

- Understand user behavior and app performance.
- Identify characteristics of successful applications.
- Compare free and paid applications.
- Analyze user reviews and sentiments.
- Support data-driven business decisions for improving app quality and user engagement.
  
**Dataset Information**

Two datasets were used in this project:

1. Google Play Store Dataset

Contains information related to Android applications, including:

- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Type (Free/Paid)
- Price
- Content Rating
- Genres
- Last Updated
- Current Version
- Android Version
  
2. User Reviews Dataset

Contains customer review information, including:

- App Name
- Translated Review
- Sentiment
- Sentiment Polarity
- Sentiment Subjectivity
  
***Libraries Used***
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

**Data Preprocessing**

The following preprocessing steps were performed before analysis:

- Removed duplicate records.
- Removed one corrupted record containing misaligned values.
- Handled missing values appropriately.
- Converted the Size column into numerical values.
- Cleaned and converted Installs into numeric format.
- Converted Price into numeric values.
- Converted Last Updated into datetime format.
- Verified data quality before visualization.

---

## Exploratory Data Analysis

The project includes **20 visualizations** covering the following analyses:

### Univariate Analysis

- Distribution of Ratings
- Distribution of Reviews
- Distribution of Installs
- Distribution of App Size
- Distribution of Price

### Categorical Analysis

- Top App Categories
- Free vs Paid Apps
- Average Rating by Category

### Bivariate Analysis

- Reviews vs Rating
- Installs vs Rating
- Free vs Paid Ratings
- Average Installs by Category
- Content Rating vs Rating
- Price vs Rating
- Size vs Rating

### Multivariate Analysis

- Correlation Heatmap

### User Review Analysis

- Distribution of User Sentiments
- Distribution of Sentiment Polarity
- Distribution of Sentiment Subjectivity
- Top 10 Apps by Average Sentiment Polarity

---

## Key Findings

- Most applications receive ratings between **4.0 and 5.0**, indicating generally positive user feedback.
- The majority of apps on the Play Store are **free**.
- Categories such as **Family**, **Games**, and **Tools** contain the largest number of applications.
- Reviews and installs exhibit a strong positive relationship, suggesting that more popular apps receive greater user engagement.
- App price shows little direct relationship with user ratings.
- User reviews are predominantly **positive**, reflecting overall customer satisfaction.
- Sentiment analysis indicates that successful apps consistently receive favorable user feedback.

---

## Business Recommendations

- Focus on app quality and user experience rather than pricing alone.
- Regularly monitor user reviews to identify improvement areas.
- Optimize app size for better accessibility and download experience.
- Encourage user engagement through timely updates and feature enhancements.
- Continuously analyze app performance metrics to support informed business decisions and long-term growth.

---

## Project Outcome

This project demonstrates how **Exploratory Data Analysis (EDA)** can transform raw application data into meaningful business insights. The findings can help developers improve application quality, enhance user satisfaction, understand customer preferences, and make data-driven decisions to increase app performance and long-term success.enhance customer satisfaction, and make informed strategic decisions for long-term growth.
