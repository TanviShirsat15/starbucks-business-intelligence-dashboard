# ☕ Starbucks Beverage Analytics Dashboard

An interactive **Power BI** dashboard built to analyze Starbucks beverage nutritional data. The dashboard provides meaningful insights into beverage categories, calories, caffeine, sugar, and protein using interactive visualizations, DAX measures, and dynamic slicers.

---

## 📸 Dashboard Preview

<img width="1389" height="786" alt="starbucks dashboard " src="https://github.com/user-attachments/assets/2519355c-c28d-446e-8e52-2860169bee90" />

---

## 📖 Project Overview

This dashboard transforms raw Starbucks beverage nutrition data into an interactive business intelligence report. Users can explore nutritional information, compare beverage categories, and identify trends through dynamic filters and visual analytics.

---

## 🎯 Objectives

- Analyze the nutritional composition of Starbucks beverages.
- Compare beverage categories based on calories, sugar, and caffeine.
- Enable users to interactively filter data using slicers.
- Present insights through clear and engaging visualizations.

---

## ✨ Key Features

- Interactive KPI Cards
- Dynamic Number Slicer (Protein Range)
- Interactive List Slicer (Beverage Preparation)
- Average Calories Analysis
- Average Caffeine Analysis
- Average Sugar Analysis
- Beverage Category Distribution
- Top 5 Highest Caffeine Beverages
- Cross-filtering across all visuals
- Starbucks-themed dashboard design

---

## 📊 Dashboard Visualizations

- KPI Cards
- Line Chart
- Clustered Bar Chart
- Donut Chart
- Number Slicer
- List Slicer
- Custom Images & Icons

---

## 📈 DAX Measures Used

```DAX
Total Beverages = DISTINCTCOUNT(starbucks[Beverage])

Average Calories = AVERAGE(starbucks[Calories])

Average Sugars = AVERAGE(starbucks[Sugars (g)])

Average Caffeine = AVERAGE(starbucks[Caffeine (mg)])
```

---

## 🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Data Visualization

---

## 📂 Dataset

The dashboard is built using the Starbucks Beverage Nutrition dataset containing information such as:

- Beverage Name
- Beverage Category
- Beverage Preparation
- Calories
- Protein (g)
- Sugars (g)
- Caffeine (mg)
- Sodium
- Calcium
- Iron
- Cholesterol
- Dietary Fibre

---

## 💡 Business Insights

This dashboard helps users:

- Compare beverages based on nutritional values.
- Identify beverages with the highest caffeine content.
- Analyze average calories and sugar across beverage categories.
- Filter beverages using protein range and beverage preparation.
- Explore beverage category distribution through interactive charts.

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Modeling
- DAX Measures
- Interactive Dashboard Design
- KPI Development
- Business Intelligence
- Data Visualization
- Power BI Report Design

---

## 📁 Repository Structure

```
Starbucks-PowerBI-Dashboard/
│
├── Starbucks Dashboard.pbix
├── Dataset.xlsx
├── Dashboard.png
├── README.md
```

---

## 🔮 Future Enhancements

- Add drill-through pages
- Add custom tooltip pages
- Include bookmarks for easier navigation
- Expand the dashboard with sales and revenue analysis
- Optimize for mobile devices

---

## 👩‍💻 Author

**Tanvi Shirsat**

Aspiring Data Analyst passionate about transforming raw data into actionable business insights using Power BI, SQL, Excel, and Python.

---

⭐ If you found this project useful, consider giving it a star!
