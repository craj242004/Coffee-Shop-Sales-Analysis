
# ☕ Coffee Shop Sales — Business Insights

## 1. Overall Sales Performance

For the February 2023 dashboard view:

- Total Sales: approximately **$76K**
- Total Orders: approximately **16.4K**
- Total Quantity Sold: approximately **23.6K**

The dashboard provides an overview of revenue, order volume, and quantity sold for the selected period.

---

## 2. Weekday vs Weekend Sales

The analysis shows a clear difference between weekday and weekend sales.

- Weekday Sales: approximately **$54K**
- Weekend Sales: approximately **$22K**
- Weekdays contributed approximately **71%** of total sales.
- Weekends contributed approximately **29%** of total sales.

### Business Interpretation

Sales activity was considerably higher on weekdays during the selected period. This suggests that weekday purchasing activity is an important contributor to overall store revenue.

---

## 3. Product Category Performance

Coffee was the leading product category in the selected dashboard period.

| Product Category | Approx. Sales |
|---|---:|
| Coffee | $29.27K |
| Tea | $21.73K |
| Bakery | $9.04K |
| Drinking Chocolate | $8.13K |
| Coffee Beans | $4.08K |
| Loose Tea | $1.28K |
| Branded | $1.24K |
| Flavours | $0.93K |
| Packaged Chocolate | $0.45K |

### Business Interpretation

Coffee and tea generated substantially more sales than the smaller product categories. These categories therefore represent major contributors to the selected period's revenue.

---

## 4. Top-Performing Products

The leading products displayed in the dashboard include:

| Product | Approx. Sales |
|---|---:|
| Barista Espresso | $10.03K |
| Brewed Chai Tea | $8.38K |
| Hot Chocolate | $8.13K |
| Gourmet brewed coffee | $7.65K |
| Brewed Black tea | $5.37K |
| Brewed herbal tea | $5.23K |
| Premium brewed coffee | $4.15K |
| Organic brewed coffee | $4.08K |
| Scone | $3.98K |

### Business Interpretation

Barista Espresso was the highest-selling product among the products displayed, followed by Brewed Chai Tea and Hot Chocolate.

The product-level analysis can be used to identify products that contribute strongly to sales and should be monitored over time.

---

## 5. Store Location Performance

The dashboard shows the following sales performance for the three store locations:

| Store Location | Approx. Sales |
|---|---:|
| Hell's Kitchen | $25.72K |
| Lower Manhattan | $25.32K |
| Astoria | $25.11K |

### Business Interpretation

Sales across the three locations were relatively close.

The difference between the highest and lowest performing locations was less than $1K for the selected period, indicating a relatively balanced sales contribution across the locations.

---

## 6. Daily Sales Performance

Daily sales were compared against the average daily sales for the selected period.

The analysis classifies each day as:

- Above Average
- Average
- Below Average

### Business Interpretation

This comparison helps identify unusually strong or weak sales days and provides a simple way to investigate daily sales patterns.

---

## 7. Hourly Sales Analysis

The dashboard includes a day-and-hour sales heatmap.

This analysis makes it possible to identify:

- High-sales hours
- Low-sales hours
- Differences between weekdays
- Differences between weekends
- Periods of concentrated customer activity

### Business Interpretation

Hourly analysis can help the business understand when customer demand is concentrated during the day and can support further analysis of staffing and operating patterns.

---

## 8. Month-over-Month Performance

The SQL analysis uses the `LAG()` window function to compare the current month with the previous month.

The project calculates month-over-month changes for:

- Sales
- Orders
- Quantity Sold

### Business Interpretation

Month-over-month analysis helps track whether revenue, order volume, and quantity sold are increasing or decreasing between consecutive months.

---

# 📌 Overall Business Takeaways

The analysis highlights several important patterns:

1. **Coffee and tea are major revenue-generating categories.**

2. **Weekday sales contribute a larger share of revenue than weekend sales** in the selected dashboard period.

3. **Barista Espresso is one of the strongest individual products** based on the displayed sales.

4. **Sales are relatively evenly distributed across the three store locations** in the selected period.

5. **Daily sales vary around the average**, making above-average and below-average days useful areas for further investigation.

6. **Sales activity changes throughout the day**, which can be explored using the hourly heatmap.

7. **Month-over-month analysis provides a way to monitor changes in sales, orders, and quantity sold over time.**

---

## 📌 Note

The numerical insights in this document refer to the period displayed in the Power BI dashboard screenshot. SQL queries in the project also demonstrate analysis for other selected months, including May 2023.

The dashboard is interactive, so results change when the selected month or other filters are changed.
