<center><img src="image/public_school.png"></center>

# 🎓 NYC SAT Performance Explorer

## 📘 Overview
This project investigates **New York City public school SAT performance** using the dataset provided in `schools.csv`. The analysis explores how schools across different boroughs perform in the three SAT components (**Math**, **Reading**, and **Writing**) and identifies trends in total SAT performance at both the school and borough levels.

The goal is to provide clear, data-driven insights into school performance variation, highlight the strongest-performing schools, and identify where performance variability is the greatest across NYC.

---

## 💾 Dataset: `schools.csv`

The dataset includes aggregated SAT statistics for public high schools in New York City.

| Column | Description |
|--------|-------------|
| `school_name` | Full name of the NYC public high school. |
| `borough` | Borough where the school is located (e.g., Manhattan, Brooklyn). |
| `building_code` | NYC school building identifier. |
| `average_math` | Average SAT Math score for the school. |
| `average_reading` | Average SAT Reading score for the school. |
| `average_writing` | Average SAT Writing score for the school. |
| `percent_tested` | Percentage of students at the school who took the SAT |
| `total_SAT` | *Computed column*: Sum of Reading + Math + Writing. |

---

## 🧠 Analysis Summary

### 1. High-Performing Math Schools
- Identified schools achieving **at least 80% of the maximum math score (≥ 640/800)**.  
- These schools represent the strongest Math performance across all boroughs.  
- Results spotlight schools with exceptional STEM-related academic strength.

---

### 2. Top Schools by Total SAT Score
- Calculated the **combined SAT score** for each school.  
- Sorted and extracted the **Top 10 schools** with the highest overall SAT performance.  
- These represent NYC’s strongest all-around academic performers across reading, writing, and math.

---

### 3. Borough-Level Standard Deviation Analysis
- Grouped schools by **borough** and computed:  
  - Number of schools  
  - Mean total SAT score  
  - Standard deviation of total SAT score  
- The borough with the **largest standard deviation** reflects the **widest performance gap**, showing where educational inequality or diversity in performance is most pronounced.

---

## 📊 Visualizations
Visual outputs included to support the analysis:
- Horizontal bar chart illustrating schools with **atleast 80% of the maximum math score**
- Horizontal bar chart showing the top 10 performing schools based on combined SAT scores

---

## 🛠️ Tools & Libraries Used
- **Python**  
- **pandas** – data transformation, grouping, aggregation  
- **matplotlib** – visualizations  
- **Jupyter Notebook**

---

## 🔍 Key Insights
- **Math Excellence:** Only a subset of schools meet the high-performance Math threshold, indicating significant variation in quantitative achievement.  
- **Top Performers:** The highest-ranking schools show consistently strong results across all SAT sections, not just Math.  
- **Borough Inequality:** One borough demonstrates a **substantially higher standard deviation**, suggesting varied performance levels among schools in the same region.  
- **Overall Trend:** Differences between boroughs reveal notable geographic disparities in academic outcomes.

---
