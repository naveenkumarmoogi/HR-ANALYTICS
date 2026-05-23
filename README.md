````md
# Day 6 — HR Analytics Dashboard

Today’s project was focused on advanced Excel formulas used in real HR and business reporting workflows.

## Project Overview
Built an HR Analytics Dashboard with:
- Employee lookup system
- Summary statistics tables
- Multi-condition formulas
- Conditional formatting

Dataset includes:
- Employee ID
- Name
- Department
- Region
- Salary
- Performance Rating
- Employee Status

25+ rows of sample HR data were used.

---

## Features Implemented

### Employee Lookup Panel
Created a dynamic search panel using `INDEX MATCH`.

Typing an employee name automatically returns:
- Department
- Region
- Salary
- Performance Rating

### Error Handling with IFERROR
Used `IFERROR` to prevent broken formula displays and return:

```excel id="lks920"
Not Found
````

for invalid employee names.

---

## HR Summary Tables

### COUNTIFS

* Count Active employees by department
* Count High Performers (Rating ≥ 4)

### SUMIFS

* Total salary cost by department

### AVERAGEIFS

* Average salary by region

---

## Conditional Formatting

Applied a performance-based color scale:

* Lower ratings → lighter colors
* Higher ratings → stronger highlight colors

This improved visibility of employee performance trends instantly.

---

## Skills Practiced

* INDEX MATCH
* IFERROR
* COUNTIFS
* SUMIFS
* AVERAGEIFS
* HR Reporting
* Spreadsheet Analytics
* Conditional Formatting

---

## Key Learning

VLOOKUP is useful for beginners.

But INDEX MATCH is more reliable because it:

* works in both directions
* survives column changes
* scales better in larger datasets

This project felt closer to a real HR reporting workflow than a practice sheet.

---

## Files Included

* ![GOOGLE SHEETS](HR_ANALYTICS_SHEET.xlsx)
* ![DASHBOARD](HR_ANALYTICS_DASHBOARD.pdf)

## Preview

![HR Dashboard](HR_ANALYTICS_DASHBOARD.pdf)
---

Day 6 completed.

#Excel #DataAnalytics #100DaysOfData #DataAnalyst #LearningInPublic

```
```
