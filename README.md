# parulmital_2511909_part4_tableau_dashboard# Part 4: Tableau Executive Dashboard & Data Storytelling

 

## Business Problem Summary

 
The retail leadership team requires an executive dashboard that provides visibility into sales performance, profitability, customer behavior, shipping performance, discount effectiveness, and return patterns.

 

The objective of this project is to transform transactional sales data into an interactive Tableau dashboard that supports business decision-making, highlights risks and opportunities, and enables leadership to monitor key performance indicators.

 

---

 

## Dataset Description

 

The dataset contains order-level sales data, including:

 

- Sales and profit values 

- Customer segment details 

- Product category and sub-category 

- Shipping mode and delivery details 

- Discount and return information 

- Regional and geographic data 

 

The dataset was provided as `dashboard_sales_data.xlsx` and used directly in Tableau.

 

---

 

## Tableau Workbook Description

 
The Tableau workbook is saved as:

 

tableau/executive_dashboard.twbx

 

The workbook contains multiple worksheets and one executive dashboard designed for leadership reporting.

 

The dashboard combines KPI monitoring, sales trends, regional performance, customer behavior, category profitability, return analysis, and shipping performance into a single executive view.

 

 

---

 

## Calculated Fields Created

 

The following calculated fields were created in Tableau:

 

- **Profit Margin** = Profit / Sales 

- **Cost** = Sales - Profit 

- **Average Order Value** = Sales / Number of Orders 

- **Return Rate** = Returned Orders / Total Orders 

- **Shipping Delay Bucket** = Categorization of delivery delay into groups (e.g., 0-2 days, 3-5 days, etc.)

 

Additional calculated fields were created to support analysis.

 

---

 

## Dashboard Components

 

The executive dashboard includes:

 

- Sales trend over time 

- Regional performance 

- Category and sub-category profitability 

- Customer segment comparison 

- Shipping and delay analysis 

- Discount vs profit relationship 

- Return analysis 

 

---

 

## Filters and Interactions Used

 

The dashboard includes interactive filters such as:

 

- Region 

- Category 

- Customer segment 

- Date range 

- Ship mode 

 

Interactive actions are used to allow users to explore data dynamically.

 

---

 

## Key Business Insights

 

- Sales trends show seasonal fluctuations across months 

- Some regions contribute high revenue but lower profit margins 

- Discount-heavy orders tend to reduce profitability 

- Certain categories consistently perform better in profit contribution 

- Shipping delays vary by ship mode and may impact customer satisfaction 

 

---

 

## Dashboard Story Summary

 

The dashboard highlights areas of business strength and concern.

 

It shows how sales are evolving over time, which regions are performing better, and where profitability is being affected due to discounts or returns.

 

The insights help leadership take data-driven decisions.

 

---

 

## Assumptions and Limitations

 

- Return data is assumed to be correctly labeled 

- Discount values are assumed to be valid unless flagged 

- Analysis is limited to available dataset (no external data used) 

- Some insights are based on aggregated data, not individual transactions 

 

---

 

## Screenshots Included

 

- Full dashboard view 

- Sales trend chart 

- Regional performance view 

- Category profitability view 

- Filter interaction example 

 

