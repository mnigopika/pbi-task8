<h1 align="center">📊 Student Performance Dashboard</h1>
<p align="center">
  <b>Explore student scores • Compare learning outcomes • Discover patterns</b>
</p>

<p align="center">
  <img alt="Power BI" src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=111111">
  <img alt="Dataset" src="https://img.shields.io/badge/Dataset-CSV-2E8B57?style=for-the-badge">
  <img alt="Records" src="https://img.shields.io/badge/Records-1%2C000-3977D5?style=for-the-badge">
</p>

## ✨ About the Project

The **Student Performance Dashboard** is a Power BI data-visualization project built around students' math, reading, and writing scores. It helps explore how performance varies across selected student and educational characteristics.

The aim is to turn a raw CSV dataset into an interactive, easy-to-understand view of student results.

## 🖼️ Dashboard Preview

> The image below is a **conceptual mockup** to illustrate a possible dashboard layout. It is not a screenshot or a verified view of the supplied `.pbix` report.

<img width="906" height="514" alt="Screenshot 2026-10-27 195746" src="https://github.com/user-attachments/assets/9de6b38f-b4e8-4237-bf57-282fa9bb961b" />


## 🎯 Project Objectives

- Summarize performance across math, reading, and writing.
- Compare scores across student groups.
- Explore patterns related to test preparation and parental education.
- Present insights in a clear, interactive dashboard format.

## 🗂️ Dataset at a Glance

| Detail | Description |
|---|---|
| Dataset file | `StudentsPerformance - StudentsPerformance(1).csv` |
| Number of records | 1,000 students |
| Number of fields | 8 |
| Score measures | Math, reading, writing |

### Dataset columns

| Column | Meaning |
|---|---|
| `gender` | Student gender |
| `race/ethnicity` | Student's race/ethnicity group |
| `parental level of education` | Reported parental education level |
| `lunch` | Standard or free/reduced lunch category |
| `test preparation course` | Test preparation course status |
| `math score` | Mathematics score |
| `reading score` | Reading score |
| `writing score` | Writing score |

## 📌 Dashboard Analysis Ideas

Depending on the visuals and filters included in the Power BI report, explore:

- **Subject comparison:** Compare average math, reading, and writing scores.
- **Group comparisons:** Explore results across gender and race/ethnicity groups.
- **Preparation:** Compare results by test preparation course status.
- **Parental education:** Investigate score patterns across education levels.
- **Lunch category:** Compare results across lunch categories.

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** — data modeling and dashboard design
- **CSV** — source dataset
- **Markdown + SVG** — project documentation and preview graphics

## 🚀 How to Use

1. Download or clone this project folder.
2. Open `studentperformance.pbix` in **Power BI Desktop**.
3. If prompted, update the data source path to the included CSV file.
4. Select **Refresh** if needed.
5. Use the available slicers and visuals to explore the report.

## 📁 Project Structure

Keep these files together so the README images display correctly:

```text
student-performance-dashboard/
├── studentperformance.pbix
├── StudentsPerformance - StudentsPerformance(1).csv
├── README.md
├── dashboard-banner.svg
└── dashboard-preview.svg
```

## 💡 Questions This Dashboard Can Help Explore

- Which subject has the highest average score?
- How do score patterns vary by student group?
- Are scores different for students who completed test preparation?
- How do results vary by parental education level?
- What differences appear across lunch categories?

## ⚠️ Notes

- The preview graphic is illustrative; replace it with a real screenshot of your Power BI report for an exact representation.
- Descriptive differences do not prove that a factor caused a change in scores.
- Confirm the actual charts, KPIs, and findings in the `.pbix` file before reporting specific conclusions.


