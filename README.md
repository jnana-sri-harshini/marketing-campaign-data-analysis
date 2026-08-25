# Marketing Campaign Data Analysis and ROI Prediction

## 📌 Project Overview

This project presents an end-to-end analysis of marketing campaign data using Python.

The main purpose of this project is to analyze marketing campaign performance, identify factors affecting Return on Investment (ROI), compare different marketing channels and customer segments, and predict campaign ROI using machine learning.

The complete workflow includes:

**Data Loading → Data Cleaning → Feature Engineering → Exploratory Data Analysis → Data Visualization → Statistical Analysis → Machine Learning → Business Insights**

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze marketing campaign performance.
- Identify the most effective marketing channels.
- Compare different campaign types.
- Analyze customer segment performance.
- Study conversion rates, clicks, impressions, and engagement.
- Analyze customer acquisition costs.
- Identify factors associated with higher ROI.
- Analyze campaign performance over time.
- Predict ROI using machine learning.
- Generate actionable business recommendations.

---

## 📊 Dataset

The dataset contains approximately **200,000 marketing campaign records** with **16 original attributes**.

### Dataset Features

| Feature | Description |
|---|---|
| Campaign_ID | Unique identifier for each campaign |
| Company | Company associated with the campaign |
| Campaign_Type | Type of marketing campaign |
| Target_Audience | Target customer group |
| Duration | Duration of the campaign |
| Channel_Used | Marketing channel used |
| Conversion_Rate | Rate at which users converted |
| Acquisition_Cost | Cost of acquiring customers |
| ROI | Return on Investment |
| Location | Location of the campaign |
| Language | Language used in the campaign |
| Clicks | Number of clicks generated |
| Impressions | Number of impressions |
| Engagement_Score | Customer engagement score |
| Customer_Segment | Customer segment targeted |
| Date | Date of the campaign |

---

## 🛠️ Technologies Used

- **Python**
- **Google Colab**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Excel**

---

## 🔄 Project Workflow

### 1. Data Loading

The dataset is loaded into a Pandas DataFrame using Python.

The project uses Google Drive to store and access the CSV dataset through Google Colab.

---

### 2. Data Understanding

The dataset is analyzed to understand its structure and characteristics.

The following operations are performed:

- Display first and last records
- Check number of rows and columns
- Identify column names
- Check data types
- Generate descriptive statistics
- Analyze categorical variables
- Check missing values
- Check duplicate records

---

### 3. Data Cleaning

The following preprocessing operations are performed:

- Missing values are checked.
- Duplicate records are identified and removed.
- Campaign duration is converted into numeric days.
- Acquisition cost is converted from currency format into numeric values.
- Date values are converted into datetime format.

---

### 4. Feature Engineering

Additional features are created to improve the analysis.

### New Features

- `Duration_Days`
- `CTR`
- `Estimated_Conversions`
- `Cost_Per_Click`
- `Cost_Per_Conversion`
- `Year`
- `Month`
- `Quarter`
- `Day_of_Week`

These features provide additional information for campaign performance analysis.

---

## 📈 Exploratory Data Analysis

Exploratory Data Analysis is performed to identify patterns and relationships within the marketing campaign data.

### Campaign Type Analysis

Different campaign types are compared based on:

- Average ROI
- Conversion Rate
- Engagement Score
- CTR
- Acquisition Cost

### Marketing Channel Analysis

Marketing channels are compared using:

- Average ROI
- Conversion Rate
- CTR
- Engagement Score
- Total Clicks
- Total Impressions

### Customer Segment Analysis

Customer segments are analyzed to determine which groups provide better campaign performance.

### Target Audience Analysis

Different target audiences are compared based on campaign performance and ROI.

### Location Analysis

Campaign performance is compared across different locations.

### Language Analysis

Campaign performance is analyzed across different campaign languages.

### Time-Based Analysis

Campaign performance is analyzed over time using:

- Year
- Month
- Quarter
- Day of Week

---

## 📊 Data Visualization

The project uses multiple visualization techniques to understand marketing performance.

### Visualizations Included

- Campaign Type vs ROI
- Channel vs ROI
- Customer Segment vs ROI
- Location vs ROI
- Conversion Rate by Campaign Type
- Conversion Rate by Channel
- Monthly ROI Trend
- Monthly Conversion Rate Trend
- ROI Distribution
- Conversion Rate Distribution
- Engagement vs ROI
- Acquisition Cost vs ROI
- Correlation Heatmap
- Channel × Campaign Type Heatmap
- Customer Segment × Channel Heatmap
- Machine Learning Feature Importance

---

## 🔎 Correlation Analysis

Correlation analysis is performed to understand relationships between important numerical variables.

The analysis includes:

- ROI
- Conversion Rate
- Acquisition Cost
- Clicks
- Impressions
- Engagement Score
- CTR
- Duration
- Cost Per Click
- Cost Per Conversion

A correlation heatmap is used to visualize these relationships.

---

## 🏆 Campaign Performance Analysis

The project identifies:

- Highest ROI campaigns
- Lowest ROI campaigns
- Best-performing campaign types
- Best-performing marketing channels
- Best-performing customer segments
- Best-performing locations
- Best-performing languages

The top-performing campaigns are extracted and stored separately for further analysis.

---

# 🤖 Machine Learning

## ROI Prediction

A **Random Forest Regression** model is used to predict marketing campaign ROI.

The machine learning workflow is:

```text
Marketing Campaign Data
          ↓
Data Preprocessing
          ↓
Categorical Encoding
          ↓
Train/Test Split
          ↓
Random Forest Regression
          ↓
ROI Prediction
          ↓
Model Evaluation
          ↓
Feature Importance
