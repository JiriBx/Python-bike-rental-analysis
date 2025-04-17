# 🚲 Bike Rentals Analysis (Fall-Winter 2023)

This project explores how different factors — like weather and holidays — impact hourly bike rentals.  
The goal was to dig into real-world data and find patterns that could help optimize fleet management or predict demand.

---

## 🧠 Problem

Bike rental companies need to plan inventory and staffing based on rental patterns.  
Understanding when and why rentals go up or down could improve service, increase revenue, and cut costs.

---

## 🎯 Goal

Analyze historical rental data to uncover:
- How weather conditions affect rental volumes
- Rental patterns across different hours and days
- Impact of holidays on demand

---

## 🛠️ How It Works

- Data: Rental counts per hour from October 1 to December 22, 2023
- Tools used: `Python`, `Pandas`, `Matplotlib`, `Seaborn`
- Missing dates (Oct 31–Nov 23) were noted but not imputed
- Correlation analysis and visualizations done for temperature, humidity, and wind speed

---

## 📊 Key Findings

- Rentals increase with temperature (up to about 80°F)
- Higher humidity and stronger winds **reduce** rentals
- Rentals peak late mornings and evenings (around commute times)
- Saturdays see the highest number of rentals; Wednesdays the lowest

---

## 🚦 What Could Be Improved
- Impute missing data for better modeling
- Add predictive modeling (e.g., regression) for forecasting
- Include more factors like event days, special discounts

---

## 📁 Repository Structure

```plaintext
data/        → sample bike rental data (optional)
notebooks/   → Jupyter notebook (`Bike_rentals_Github.ipynb`)
output/      → charts/graphs (optional)
README.md    → you're reading it
requirements.txt → install dependencies

Built by [Jiri](https://github.com/jiribx), product manager passionate about making data-driven decisions easy and accessible.
