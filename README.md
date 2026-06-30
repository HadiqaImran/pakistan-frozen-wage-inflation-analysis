# When Salaries Don't Keep Up: A Look at Inflation's Impact on Frozen Wages in Pakistan 🇵🇰

A data analytics project exploring how inflation affects the real value of a stagnant wage in Pakistan using **Python (Pandas)** for data processing and **Power BI** for visualization.

---

## Project Background

Pakistan revises its statutory minimum wage periodically, but not every worker benefits from those revisions. In informal businesses, small private firms, and daily-wage jobs, workers may go years without meaningful salary increases.

This raised an interesting question:

> **If a worker's salary remained stagnant while inflation continued to rise, how quickly would their purchasing power disappear?**

Rather than using another tutorial dataset, I wanted to build a project around a real-world issue while strengthening my Python data analysis skills.

---

## Project Overview

This project models a simple **what-if scenario**:

- A worker earns Pakistan's **2014 statutory minimum wage (Rs. 10,000)**.
- Their salary remains unchanged until **2024**.
- Inflation follows Pakistan's actual annual inflation rates over the same period.

Using this model, the project estimates how inflation affects the **real (inflation-adjusted)** value of a stagnant wage and visualizes the results through an interactive Power BI dashboard.

---

## Objectives

- Analyze the impact of inflation on a stagnant wage.
- Convert nominal wages into inflation-adjusted (real) wages.
- Practice data cleaning and transformation using Pandas.
- Create an interactive dashboard using Power BI.
- Communicate findings through data storytelling.

---

## Data Sources

| Dataset | Source |
|---------|--------|
| Inflation (CPI, annual %) | World Bank |
| GDP (Current US$) | World Bank |
| Pakistan Statutory Minimum Wage | International Labour Organization (ILO) |

---

## Methodology

The analysis assumes a worker's nominal salary remained fixed at **Rs. 10,000**, Pakistan's statutory minimum wage in 2014.

A cumulative inflation factor was constructed using Pakistan's annual inflation data. The frozen salary was then converted into **constant 2014 rupees** to estimate its real purchasing power over time.

> **Note:** This is a scenario model rather than an analysis of Pakistan's actual minimum wage policy. Pakistan's statutory minimum wage increased multiple times between 2014 and 2024, whereas this model intentionally assumes the worker received no salary increases.


---

## Key Findings

- 📈 Inflation peaked at **30.77%** in **2023**, the highest value in the dataset.

- 💸 Under the frozen-wage scenario, a salary fixed at **Rs. 10,000** in 2014 declined to an estimated **inflation-adjusted value of Rs. 3.66k** by 2024.

- 📊 Compared with Pakistan's **2024 statutory minimum wage (Rs. 37,000)**, the modeled frozen wage shows a **90.10% gap**, illustrating how dramatically inflation can affect workers whose wages fail to keep pace.

- 📈 Meanwhile, Pakistan's statutory minimum wage increased by **270%** over the same period (**Rs. 10,000 → Rs. 37,000**), highlighting a very different outcome for workers whose salaries were revised alongside policy changes.

---

## Skills Demonstrated

- Python
- Pandas
- Data Cleaning
- Data Transformation
- Inflation Adjustment
- Exploratory Data Analysis (EDA)
- Data Visualization
- Dashboard Design
- Power BI
- Data Storytelling

---

## Limitations

This project models a hypothetical worker whose salary remained unchanged throughout the decade.

It should **not** be interpreted as an analysis of Pakistan's overall labour market or the purchasing power of all workers. Instead, it demonstrates how inflation can affect incomes that fail to keep pace with rising prices under a clearly defined set of assumptions.

---

## Future Improvements

Possible extensions include:

- Use monthly CPI data instead of annual inflation rates.
- Compare the scenario with average wages across different industries.
- Analyze provincial minimum wage differences.
- Add interactive Power BI filters for year and economic indicators.
- Incorporate household income data for a broader labour market analysis.

---

## Tools & Technologies

- Python
- Pandas
- Jupyter Notebook
- Power BI

---



## Key Takeaway

This project reinforced an important lesson for me:

> **Good data analytics isn't just about writing code or building dashboards. It's about asking meaningful questions, defining assumptions clearly, understanding the limitations of your data, and communicating insights honestly.**
