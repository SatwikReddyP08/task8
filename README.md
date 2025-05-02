# Task 8: Simple Sales Dashboard

## Objective
Create an interactive Power BI dashboard to visualize sales performance by product, region, and month, per Elevate Labs' Task 8.

---

## Dataset Used
- **superstore_sales.csv**: Global Superstore dataset with ~51,290 rows, including:
  - `order_date`: Date of sale (e.g., 01/01/2011)
  - `region`: Geographic region (e.g., Africa, Oceania)
  - `category`: Product category (e.g., Office Supplies, Furniture)
  - `sales`: Revenue per order
  - `profit`: Profit per order
  - `quantity`: Units sold

---

## Tools Used
- **Power BI Desktop**: For data import, visualization, and dashboard creation

---

## Visualizations Created
1. **Sales Trend by Month**  
   - *Type*: Line Chart  
   - *Details*: Shows total sales over months using Power BI’s date hierarchy (Month-Year).  
   - *Insight*: Identifies peak sales months.

2. **Sales by Region**  
   - *Type*: Bar Chart  
   - *Details*: Compares sales across regions, with colors highlighting top performers.  
   - *Insight*: Shows leading regions.

3. **Sales by Category**  
   - *Type*: Donut Chart  
   - *Details*: Displays sales distribution by product category.  
   - *Insight*: Highlights dominant categories.

4. **Slicer**  
   - *Details*: Region slicer for interactive filtering of visuals.

---

## File Structure
- `superstore_sales.csv`: Raw dataset
- `sales_dashboard.pbix`: Power BI dashboard file
- `sales_dashboard.png`: Dashboard screenshot (or .pdf)
- `insights.txt`: 3–4 key insights from the dashboard
- `README.md`: This file

---

## How to Run
1. Clone this repository.
2. Open `sales_dashboard.pbix` in Power BI Desktop.
3. Use the region slicer to filter and explore visuals.
4. Check `insights.txt` for key findings.

---

## Learnings
- **Power BI**: Imported raw CSV, used date hierarchy for Month-Year, and created line, bar, and donut charts.
- **Slicers**: Added a region slicer for dynamic filtering.
- **Dashboard Design**: Arranged visuals cleanly, used consistent colors, and highlighted top performers.
- **Insights**: Learned to identify trends like top regions and peak months for business users.
- **Challenges**: Ensured `sales` was numeric and `order_date` displayed correctly with minimal transformations.

---

## Insights
- Detailed in `insights.txt`, covering top regions, categories, and sales trends.

---

## Author
Satwik Reddy Pathapati
