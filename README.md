# parulmital_2511909_part4_tableau_dashboard
1 # Part 4: Tableau Executive Dashboard &amp; Data Storytelling
2
3 ## Business Problem Summary
4
5 In this assignment, the objective was to design an executive
dashboard for retail leadership.
6 The goal was to monitor key business metrics such as sales
performance, profitability, customer segments, category trends,
discount impact, and shipping performance.
7
8 The dashboard is intended to help leadership identify business
opportunities, risks, and areas requiring attention.
9
10 ---
11
12 ## Dataset Description
13
14 The dataset contains order-level sales data, including:
15
16 - Sales and profit values
17 - Customer segment details
18 - Product category and sub-category
19 - Shipping mode and delivery details
20 - Discount and return information
21 - Regional and geographic data
22
23 The dataset was provided as `dashboard_sales_data.xlsx` and
used directly in Tableau.
24
25 ---
26

27 ## Tableau Workbook Description
28
29 The Tableau workbook `executive_dashboard.twbx` includes
multiple sheets and one final executive dashboard.
30
31 The dashboard combines multiple views into a single interface
for decision-making.
32
33 ---
34
35 ## Calculated Fields Created
36
37 The following calculated fields were created in Tableau:
38
39 - **Profit Margin** = Profit / Sales
40 - **Cost** = Sales - Profit
41 - **Average Order Value** = Sales / Number of Orders
42 - **Return Rate** = Returned Orders / Total Orders
43 - **Shipping Delay Bucket** = Categorization of delivery delay
into groups (e.g., 0-2 days, 3-5 days, etc.)
44
45 Additional calculated fields were created to support analysis.
46
47 ---
48
49 ## Dashboard Components
50
51 The executive dashboard includes:
52
53 - Sales trend over time
54 - Regional performance
55 - Category and sub-category profitability
56 - Customer segment comparison
57 - Shipping and delay analysis
58 - Discount vs profit relationship
59 - Return analysis
60
61 ---
62
63 ## Filters and Interactions Used
64
65 The dashboard includes interactive filters such as:
66

67 - Region
68 - Category
69 - Customer segment
70 - Date range
71 - Ship mode
72
73 Interactive actions are used to allow users to explore data
dynamically.
74
75 ---
76
77 ## Key Business Insights
78
79 - Sales trends show seasonal fluctuations across months
80 - Some regions contribute high revenue but lower profit
margins
81 - Discount-heavy orders tend to reduce profitability
82 - Certain categories consistently perform better in profit
contribution
83 - Shipping delays vary by ship mode and may impact customer
satisfaction
84
85 ---
86
87 ## Dashboard Story Summary
88
89 The dashboard highlights areas of business strength and
concern.
90
91 It shows how sales are evolving over time, which regions are
performing better, and where profitability is being affected due
to discounts or returns.
92
93 The insights help leadership take data-driven decisions.
94
95 ---
96
97 ## Assumptions and Limitations
98
99 - Return data is assumed to be correctly labeled
100 - Discount values are assumed to be valid unless flagged
101 - Analysis is limited to available dataset (no external data
used)

102 - Some insights are based on aggregated data, not individual
transactions
103
104 ---
105
106 ## Screenshots Included
107
108 - Full dashboard view
109 - Sales trend chart
110 - Regional performance view
111 - Category profitability view
112 - Filter interaction example
