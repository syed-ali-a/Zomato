# 🍽️ Zomato Restaurant Analysis

This data analytics project explores customer preferences and restaurant characteristics on Zomato using exploratory data analysis (EDA), statistical hypothesis testing, and visualization.

## 📌 Problem Statement
Zomato wants to understand what makes a restaurant successful and how various factors like location, services, price, and cuisine influence customer ratings and engagement.

## 🎯 Objectives
- Identify patterns in restaurant types, services, and locations.
- Explore relationships between online ordering, table booking, and ratings.
- Use statistical testing to validate hypotheses.
- Deliver actionable insights to enhance Zomato’s strategy.

## 📊 Dataset
Sourced from Zomato’s Bangalore data, containing:
- Restaurant name, location, rating, vote count, online order/table booking options, cuisines, cost, etc.

---

## 📈 Exploratory Data Analysis (EDA)
- Cleaned data: removed nulls, duplicates, and converted data types.
- Visualizations using Seaborn, Matplotlib.
- Compared top restaurant types, locations, and features.

## 🧪 Hypothesis Testing Summary

| Question | Method | Result |
|----------|--------|--------|
| Does online order depend on restaurant type? | Chi-square | Strong association (p ≈ 0) |
| Does table booking affect rating? | Chi-square | Significant dependency (p ≈ 0) |
| Do mean ratings differ across top 5 locations? | ANOVA | Yes (p ≈ 0) |
| Correlation between votes & rating? | Pearson | Moderate positive (r = 0.43) |
| Does cost per person differ by rating category? | ANOVA | Yes (p ≈ 0) |
| Correlation between number of cuisines & rating? | Pearson | Weak positive (r = 0.10) |

---

## 💡 Recommendations
- Promote online orders for fast food & casual dining.
- Invest more in top-performing areas like Koramangala, Indiranagar.
- Encourage restaurants to enable table booking.
- Highlight high-rated restaurants with most votes.
- Suggest restaurants offer 3+ cuisines.
- Showcase value-for-money options based on pricing and rating.

---

## 🛠️ Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scipy, Statsmodels)
- Jupyter Notebook
- Statistical Testing (Chi-Square, ANOVA, Pearson)

---

## 📌 Conclusion
This project uncovers key insights into what drives customer satisfaction on Zomato. It combines visual storytelling with statistical rigor, offering actionable business recommendations based on data.

