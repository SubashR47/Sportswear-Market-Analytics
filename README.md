# Decoding Consumer Trends & Product Strategy in India’s Sportswear Market

## Business Intelligence & Sentiment Analytics Project

This project analyzes consumer trends, pricing strategy, customer sentiment, and product performance in India’s sportswear market using Python-based Business Intelligence and Natural Language Processing (NLP) techniques.

The project was developed as part of the MBA Business Analytics coursework and focuses on translating data into strategic business decisions for sportswear brands such as Nike and Adidas.

---

# Project Objective

The primary objective of this project is to build a data-driven decision framework that helps answer key business questions such as:

- Which product categories perform best in the Indian market?
- What drives customer satisfaction and engagement?
- How does pricing influence customer perception?
- Which products should be scaled, improved, or discontinued?
- What future opportunities exist in the sportswear segment?

The project combines:
- Market Performance Analysis
- Customer Sentiment Analysis
- Product Intelligence
- Competitive Positioning
- Strategic Recommendations

---

# Business Problem

India’s sportswear market is rapidly expanding due to:
- increasing fitness awareness,
- growth in athleisure demand,
- rising disposable income,
- and digital commerce adoption.

Global brands need quantitative insights to:
- optimize product portfolios,
- improve customer satisfaction,
- strengthen pricing strategy,
- and identify future growth opportunities.

This project simulates a consulting-style analytics engagement for a sportswear brand operating in India.

---

# Datasets Used

## 1. Adidas vs Nike Dataset
Contains:
- product listings,
- pricing information,
- discounts,
- brand-level positioning data.

Used for:
- pricing analysis,
- competitive positioning,
- discount strategy analysis.

---

## 2. Nike Product Review Dataset
Contains:
- product names,
- categories,
- ratings,
- review counts,
- product descriptions.

Used for:
- sentiment analysis,
- engagement analysis,
- product intelligence,
- success scoring.

---

# Technologies & Tools Used

| Component | Technology |
|---|---|
| Programming Language | Python |
| Notebook Environment | Jupyter Notebook |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| NLP & Sentiment Analysis | TextBlob |
| Text Visualization | WordCloud |
| IDE | Visual Studio Code |
| Version Control | GitHub |

---

# Project Modules

## Module 1 — Market Performance Analysis

This module focuses on:
- pricing patterns,
- category-level analysis,
- brand positioning,
- demand trends.

### Key Analyses
- Brand-wise average pricing
- Price distribution analysis
- Product category performance
- Competitive positioning

### Business Insights
- Nike maintains premium market positioning.
- Mid-premium products dominate the market.
- Running and training categories generate stronger engagement.

---

## Module 2 — Customer Sentiment Analysis

This module applies NLP techniques to identify customer perception patterns.

### Key Analyses
- Sentiment polarity scoring
- Positive vs negative sentiment distribution
- WordCloud generation
- Common keyword extraction
- Voice of Customer summary

### Key Findings
Customers strongly prioritize:
- comfort,
- lightweight design,
- breathability,
- athletic performance,
- durability.

---

## Module 3 — Product Performance Intelligence

This module evaluates product-level performance using multi-metric analysis.

### Key Analyses
- Success score generation
- Top-performing products
- Bottom-performing products
- Risk product identification
- High-potential product analysis

### Strategic Classification
Products were classified into:
- Scale
- Fix
- Drop

based on:
- customer ratings,
- sentiment,
- engagement levels.

---

## Module 4 — Trend & Correlation Analysis

This module identifies statistical relationships between:
- price,
- ratings,
- sentiment,
- customer engagement.

### Key Analyses
- Correlation heatmap
- Price vs rating analysis
- Price vs engagement analysis
- Rating vs sentiment analysis

### Key Findings
- Premium pricing alone does not guarantee satisfaction.
- Value-for-money products drive stronger engagement.
- Higher-rated products attract significantly more reviews.

---

# Success Score Logic

A custom product success score was developed using:

- 70% weight → customer ratings
- 30% weight → normalized review engagement

This score helps identify:
- future high-potential products,
- risky products,
- sustainable product performers.

---

# Strategic Recommendations

## Product Strategy
- Expand high-performing products.
- Improve moderate-performing products through pricing and quality optimization.
- Discontinue persistently weak products.

---

## Pricing Strategy
- Avoid unsupported premium pricing.
- Focus on mid-premium pricing segments.
- Reduce excessive discount dependency.

---

## Customer Strategy
- Prioritize comfort and performance features.
- Improve value perception.
- Respond faster to negative customer experiences.

---

## Market Positioning Strategy
- Strengthen performance-first branding.
- Expand training and running categories.
- Invest in future high-potential products.

---

# Key Business Findings

- Approximately 68% of products demonstrated positive sentiment.
- Nike products maintain an estimated 46% price premium compared to competitors.
- Around 42% of products qualified for “Scale” classification.
- Customer comfort and lightweight design are major purchase drivers.
- Review engagement correlates more strongly with ratings than with pricing.

---

# Project Outputs

The project includes:
- Business Intelligence Notebook
- Executive Presentation
- Strategic Recommendation Framework
- Visual Analytics Dashboard
- NLP-Based Customer Intelligence

---

# Repository Structure

```text
CA1-Sportswear-Market-Analytics/
│
├── notebook/
│   └── sportswear_analysis.ipynb
│
├── presentation/
│   └── Sportswear_Analytics_Presentation.pptx
│
├── data/
│   ├── adidas_vs_nike.csv
│   └── nike_reviews.csv
│
└── README.md
