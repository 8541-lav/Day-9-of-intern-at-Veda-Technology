Day 9 – Descriptive Statistics Primer
Internship
Organization: Veda Technology
Track: Data Analytics
Task: Day 9 – Descriptive Statistics Primer
Objective
Calculate and interpret descriptive statistics for key numeric columns in the Global Superstore dataset.
Dataset
Global Superstore dataset (GlobalSuperstore.xlsx), using the numeric columns:
- Sales
- Quantity
- Discount
- Profit
Statistics Calculated
The Day9_Statistics worksheet summarizes:
- Mean
- Median
- Mode
- Standard deviation
- 25th percentile (P25)
- 75th percentile (P75)
Summary Results
Statistic	Sales	Quantity	Discount	Profit
Mean	246.49	3.48	0.14	28.61
Median	85.05	3	0	9.24
Mode	12.96	2	0	0
Standard deviation	487.57	2.28	0.21	174.34
25th percentile (P25)	30.76	2	0	0
75th percentile (P75)	251.05	5	0.20	36.81


Values are rounded for presentation. Ensure the formulas in the workbook reference the correct source sheet and complete data range.
Interpretation
- Sales are right-skewed because the mean is substantially higher than the median. Some high-value sales raise the average.
- Sales have considerable spread: the standard deviation is high relative to the median.
- Profit also varies considerably, and its mean is higher than its median.
- The median and mode of Discount are zero, indicating that zero discount is a common value and at least half of observations have no discount.
- The middle 50% of sales fall approximately between 30.76 (P25) and 251.05 (P75).
Tools
- Excel / Google Sheets
- Descriptive-statistics formulas
How to Use
1. Open the workbook.
2. Review the original data worksheet.
3. Open Day9_Statistics to view the summary table.
4. Review this README and the project report for the interpretation.
Deliverables
- Workbook containing the summary statistics table
- This README file
- Day 9 project report
