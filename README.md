# 📊 Google Play Store App Analysis – Power BI Dashboard

## Project Overview

This project presents an **interactive Power BI dashboard** developed to analyze Google Play Store application data.

The dashboard provides insights into **app categories, ratings, reviews, installations, pricing, app types, content ratings, and app sizes**. It transforms raw Google Play Store data into interactive visualizations and key performance indicators to support clear data-driven analysis.



## Project Objectives

The main objectives of this project are:

* Analyze the distribution of applications across categories.
* Understand app ratings and review patterns.
* Compare **Free and Paid** applications.
* Analyze application installations.
* Examine app pricing and size.
* Analyze content rating distribution.
* Identify categories with high application performance.
* Provide an interactive dashboard for exploring app-level insights.
* Present important metrics using KPIs and visualizations.

---

## Dataset

The project uses a **Google Play Store application dataset** containing information about applications available on the Google Play Store.

### Important Fields

| Field              | Description                    |
| ------------------ | ------------------------------ |
| **App**            | Name of the application        |
| **Category**       | Application category           |
| **Rating**         | Average user rating            |
| **Reviews**        | Number of user reviews         |
| **Size**           | Application size               |
| **Installs**       | Number of installations        |
| **Type**           | Free or Paid                   |
| **Price**          | Application price              |
| **Content Rating** | Target audience classification |

---

## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Microsoft Excel / CSV**
* **Data Visualization**
* **Data Modeling**

---

## Project Workflow

```text
Raw Dataset
     ↓
Data Import
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
Data Modeling
     ↓
DAX Measures
     ↓
KPI Creation
     ↓
Interactive Visualizations
     ↓
Dashboard Design
     ↓
Insights & Analysis
```

---

## Data Cleaning & Transformation

The dataset was prepared using **Power Query** before creating the dashboard.

The major transformation steps include:

* Removing unnecessary columns.
* Handling missing values.
* Removing duplicate records.
* Cleaning numeric fields.
* Transforming installation values into usable numeric values.
* Cleaning price values.
* Standardizing data types.
* Preparing categorical fields for analysis.
* Creating suitable fields for dashboard reporting.

---

## Data Modeling

The Power BI model was structured to support efficient analysis and interactive filtering.

Dimension tables were created for important categorical attributes such as:

* **Category**
* **Type**
* **Content Rating**
* **Date**

These tables support filtering, analysis, and dashboard interactions.

---

# Dashboard Pages

The dashboard is organized into multiple analytical sections.

## 1. Executive Overview

Provides a high-level summary of the Google Play Store dataset.

### Key Information

* Total Apps
* Total Reviews
* Total Installs
* Average Rating
* Free Apps
* Paid Apps

### Visualizations

* App distribution by category
* App type distribution
* Rating overview
* Installation analysis
* Content rating distribution

---

## 2. App Performance

This page focuses on application performance.

### Analysis Includes

* App ratings
* Review counts
* Installation trends
* Category performance
* Most reviewed applications
* Highly installed applications

The page helps identify patterns in application popularity and user engagement.

---

## 3. Pricing & App Size

This page analyzes the relationship between application pricing and size.

### Analysis Includes

* Free vs Paid applications
* App price distribution
* App size distribution
* Average app size
* Paid app analysis
* Category-wise pricing patterns

---

## 4. Summary

The Summary page provides a consolidated view of the major findings from the dashboard.

It highlights:

* Important KPIs
* Category-level insights
* App performance
* Pricing patterns
* User engagement
* Installation patterns



# Key Performance Indicators (KPIs)

The dashboard includes important KPIs such as:

| KPI                  | Purpose                            |
| -------------------- | ---------------------------------- |
| **Total Apps**       | Total number of applications       |
| **Total Reviews**    | Total number of user reviews       |
| **Total Installs**   | Total application installations    |
| **Average Rating**   | Overall average app rating         |
| **Free Apps**        | Number of free applications        |
| **Paid Apps**        | Number of paid applications        |
| **Average Price**    | Average price of paid applications |
| **Average App Size** | Average application size           |

---

# Dashboard Visualizations

The dashboard uses multiple Power BI visuals, including:

*  Bar Charts
*  Column Charts
*  Pie / Donut Charts
*  Tables
*  KPI Cards
*  Distribution Visuals
*  Slicers
*  Navigation Buttons

Interactive slicers allow users to filter the dashboard based on different application attributes.

---

# Interactive Features

The dashboard includes interactive features such as:

* Category filters
* App type filters
* Content rating filters
* Navigation buttons
* Interactive charts
* Cross-filtering
* KPI cards
* Multiple dashboard pages

Users can interact with the visuals to explore different aspects of the Google Play Store dataset.

---

# Key Insights

The dashboard helps answer questions such as:

* Which app categories contain the most applications?
* Which categories have the highest installations?
* What is the distribution of free and paid applications?
* How are application
