# ⚽ Beyond the Scoreboard: Discovering Hidden Sports Fan Personas with Data

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Clustering-orange)
![Unsupervised Learning](https://img.shields.io/badge/Model-KMeans-green)
![Dataset](https://img.shields.io/badge/Data-2.2K%20Fans-lightgrey)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## Overview

During major sporting events such as the FIFA World Cup, millions of fans watch the same matches, follow the same teams, and engage with the same content.

Yet sports audiences are far from homogeneous.

Some fans spend heavily on merchandise and premium content. Others engage primarily through streaming platforms and social media. Some follow sports year-round, while others only participate during major events.

This project applies **unsupervised machine learning** to explore whether sports fans naturally form distinct behavioral segments.

Using data from **2,200 sports fans across 15 countries**, clustering techniques were used to uncover hidden audience structures based on engagement patterns, spending behavior, digital activity, and event participation.

The resulting clusters were interpreted as fan personas that provide a more nuanced understanding of sports audiences.

---

## Research Question

> Do sports fans naturally form distinct behavioral groups based on how they engage with sports?

This project investigates whether behavioral data can reveal meaningful audience segments without relying on predefined labels.

---

## Objectives

* Explore global sports fan behavior
* Analyze engagement and consumption patterns
* Discover hidden audience segments using clustering
* Interpret clusters as fan personas
* Generate insights about sports audience diversity

---

## Dataset Overview

### Global Sports Fan Survey 2024

* 👥 2,200 sports fans
* 🌍 15 countries
* ⚽ 26 sports represented
* 📊 42 demographic and behavioral features

### Feature Categories

#### Fan Engagement

* Viewing frequency
* Weekly watching hours
* Streaming subscriptions
* Social media activity

#### Spending Behavior

* Merchandise spending
* Pay-per-view spending
* Total annual sports spending
* Additional spending willingness

#### Event Participation

* Stadium attendance
* Fantasy sports participation
* Sports betting participation

#### Fan Profile

* Age
* Income bracket
* Education level
* Country

---

## Methodology

This project follows a standard unsupervised learning workflow:

```text
Data Cleaning
      ↓
Feature Selection
      ↓
Encoding & Scaling
      ↓
K-Means Clustering
      ↓
Cluster Evaluation
      ↓
Persona Interpretation
```

### Techniques Used

* Exploratory Data Analysis (EDA)
* Missing Value Handling
* One-Hot Encoding
* StandardScaler
* K-Means Clustering
* Elbow Method
* Silhouette Analysis

---

## Feature Selection

The clustering model was designed to capture multiple dimensions of fan behavior.

### Engagement & Loyalty

* Fan loyalty score
* Weekly watching hours
* Watch frequency

### Digital Behavior

* Streaming subscriptions
* Social media activity

### Event Participation

* Stadium visits per year

### Spending Behavior

* Merchandise spending
* Pay-per-view spending
* Additional spending willingness

### Contextual Variables

* Age
* Income bracket
* Primary motivation

---

## Clustering Results

Multiple values of K were evaluated using both the Elbow Method and Silhouette Score.

After balancing statistical performance with interpretability, the final model was configured with:

### K = 5 Clusters

The model identified five distinct behavioral segments within the sports fan population.

To simplify communication and interpretation, these technical clusters were grouped into broader fan personas.

---

## Interpreting the Clusters

### 🏆 Premium Fans

Highly engaged and financially committed sports fans.

**Characteristics**

* Highest spending levels
* Strong engagement across channels
* Frequent event participation
* Strong loyalty indicators

**Role within the audience**

* Represent the most invested fan segment

---

### 📱 Digital Fans

Fans whose engagement is primarily driven by content consumption.

**Characteristics**

* High streaming activity
* Strong digital engagement
* Active social media usage
* Lower physical attendance

**Role within the audience**

* Represent a highly active digital audience

---

### ⚽ Casual Fans

Fans with lower engagement intensity and spending activity.

**Characteristics**

* Occasional viewing behavior
* Limited spending activity
* Lower participation levels
* Less frequent interaction with sports content

**Role within the audience**

* Represent a large portion of event-driven audiences

---

## Key Findings

### 1. Sports Fans Are Not a Homogeneous Audience

The analysis revealed clear behavioral differences between fans despite their shared interest in sports.

### 2. Five Distinct Clusters Emerged from the Data

Unsupervised learning identified multiple audience segments without predefined labels.

### 3. Behavioral Patterns Created the Strongest Separation

Viewing habits, spending activity, and engagement behavior contributed more visibly to cluster differentiation than demographic characteristics alone.

### 4. Similar Demographics Can Produce Very Different Behaviors

Fans with similar ages or backgrounds often displayed substantially different consumption and engagement patterns.

---

## Why This Matters

Understanding audience behavior is relevant across multiple areas of the sports ecosystem.

### 🏟 Sports Organizations

* Better understand fan diversity
* Support audience research initiatives
* Improve fan experience design

### 📺 Streaming Platforms

* Understand viewing behavior patterns
* Explore audience engagement trends

### 🎪 Event Organizers

* Better understand participation behavior
* Analyze attendance-related patterns

### 🎯 Marketing & Analytics Teams

* Move beyond one-size-fits-all audience assumptions
* Develop more informed audience strategies

---

## Interactive Dashboards

Interactive dashboards were developed using Looker Studio to complement the analysis.

### Dashboards Included

* Sports Fan Overview Dashboard
* Fan Engagement Dashboard
* Fan Persona Dashboard

**Live Dashboard: [click here](https://datastudio.google.com/reporting/60915f04-d979-4765-a0e0-d3673d2fd4d1)**

---

## Tools & Technologies

### Programming & Analysis

* Python
* Pandas
* NumPy

### Machine Learning

* Scikit-Learn
* K-Means Clustering

### Visualization

* Matplotlib
* Seaborn

### Business Intelligence

* Looker Studio

---

## Project Structure

```text
📦 beyond-the-scoreboard
│
├── 📊 notebooks
│   └── sports_fan_segmentation.ipynb
│
├── 📂 data
│   └── sports_fan_survey_2024.csv
│
├── 📈 dashboards
│   └── looker_dashboard_links.txt
│
├── 📑 presentation
│   └── final_presentation.pptx
│
└── 📄 README.md
```

---

## Conclusion

This project demonstrates how unsupervised machine learning can be used to uncover hidden structures within sports audiences.

Rather than viewing sports fans as a single group, the analysis revealed multiple behavioral segments that differ in how they engage, consume, and participate in sports-related activities.

The findings suggest that understanding fan behavior provides a richer perspective on sports audiences than relying solely on traditional demographic categories.

---

## Final Thought

> Millions of people may watch the same match, but data reveals that they do not experience sports in the same way.

Machine learning helps uncover those differences and transform raw behavioral data into meaningful audience insights.

---

## Author

**Maryam Skaik**

Computer Science Graduate
Data Science & Machine Learning Learner
