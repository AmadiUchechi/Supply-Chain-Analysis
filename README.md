# Uniquexcel Supply-Chain-Analysis 
This project analyzes Uniquexcel's makeup product supply chain data to identify operational challenges and provide data driven recommendations for improving inventory management, supplier performance, transportation efficiency, product quality, and profitability.

Using Microsoft Excel, the raw supply chain dataset was cleaned, analyzed, and transformed into an interactive dashboard that allows key supply chain performance indicators to be monitored in one place.

The analysis focuses on answering five key business questions
1. Which SKUs are at risk of stockouys?
2. Which suppliers or routes are causing delays or high costs?
3. Are defect rates linked to suplliers or manufacturing lead times?
4. What is the profitability of each product?
5. Is transportation mode related to shipping cost?

# Business Problem
Uniquexcel faces several suppl,y chain challenges that could negatively affect operational efficiency and profitability, including:
1. High stockout risk across skincare and haircare products
2. Supplier quality issues
3. Long supplier and manufacturing lead times
4. Differences in shipping costs across routes and suppliers
5. Significant differences in profitability across SKUs

If these issues are not properly managed, they can result in lost sales, emergency replenishment costs, product defects, customer complaints, inefficient inventory allocation, and reduced profitability.

The objective of this project was therefore to use supply chain data to identify these problem areas and recommend practical actions for management.

# Tools and Skills Used
1. Microsoft Excel
2. Data Cleaning
3. Excel Tables
4. Pivot Tbales
5. Pivot Charts
6. Excel Formulas
7. Conditional Logic
8. Data Aggregation
9. CorrelatioN Analysis
10. KPI development
11. Dashboard Design
12. Supply chain Analysis
13. Business Problem Solving
14. Data Visualization

# Dashboard
The Excel Dashboard provides a consolidated view of important supply chain metrics, including:
1. Total Shipping Costs
2. Average Manufacturing Lead Time
3. Average Defect Rate
4. Average Product Cost
5. Stockout Risk by Product Type
6. Supplier Performance
7. Route Performance
8. Transportation Costs
9. Product Profitability

<img width="1753" height="742" alt="image" src="https://github.com/user-attachments/assets/2af5b10d-453f-4285-b7f1-28eebdc971d2" />


The dashboard makes it easier to identify exceptions and prioritize areas requiring management attention.

# Key Findings
#1. Stockout Risk
High-risk stockout records exceeded low-risk records in both major product categories
1. Skincare: 135 high-risk records
2. Haircare: 118 high-risk records
3. SKU152 and SKU372 had the most severe shortages, with availability 96 units below order quantity.

Other signioficant shortages  included SKU35, SKU427, SKU195, SKU391, SKU83, SKU432, and SKU487.

# 2. Routes and Supplier Performance
Route C had the longest average lead time at approximately 16.05 days.
Route B provided the best combination of lead time and shipping cost

. Average lead time: 15.30 days
. Average shipping cost: $5.25

Supplier analysis also identified:
. Supplier 4 with the longest supplier lead time of approximately 17.04 dyas
. Supplier 4 manufacturing lead time of approximately 16.35 days
. Supplier 5 with the highest average shipping cost of approximately $5.71

# 3. Supplier Quality
Supplier 1 recorded the highest average defect rate at approximately 2.80%, followed by Supplier 3 at 2.72%.
Supplier 4 had the lowest average defect rate at approximately 2.35%, despite having the longest manufacturing lead time.
The correlation between manufacturing lead time and defect rate was approximately 0.02, indicating almost no relationship between the two variables.

# 4. Product Profitability
Net Profitability was calculated as: 

# Net profitability = Revenue - Shipping Cost - Manufacturing Cost

The five strongest products were:
SKU                                         Net Profitability
SKU198                                               $976.02
SKU146                                               $968.80
SKU393                                               $960.15
SKU208                                               $956.36
SKU378                                               $948.36

The weakest-performing products included:
SKU                                         Net Profitability
SKU61                                                $10.08
SKU184                                               $15.62
SKU169                                               $29.60
SKU299                                               $29.64
SKU271                                               $31.96

# 5. Transportation Mode
Average shipping costs were relatively similar across transportation modes:

. Air:  approximately $5.54
. Rail: approximately $5.48
. Road: approximately $5.39

The difference between Air and Road was only approximately $0.16 per shipment.

This suggests that transportation mode has a relatively weak practical relationship with shipping costs in this datase.

# Recommendations
Based on the dashboard analysis, the following actions are recommended:

# Immediate Actions

Replenish high-risk SKUs
Prioritize SKU152, SKU372, and other products experiencing severe inventory shortages. Implement reorder points based on expected demand during lead times and appropriate safety stock.

Improve Supplier Quality
Focus quality improvemt initiatives on Supplier 1 and 3 by increasing incoming quality inspections and monitoring supplier defect performance.

# Near Term Actions

Optimize Transportation Routes
Test shifting appropriate shipment volumes toward Route B, which provides a better combination of shipping cost and lead time

Improve Supplier Performance
Place supplier 4 under a lead time improvement process and renegotiate Supplier 5's freight costs.

# Ongoing Actions

Monitor Product Profitability
Review SKU-level profitability monthly. Protect production capacity and inventory for high-performing products while reviewing pricing, costs, suppliers, and shipping strategies for low-performing SKUs.

# Transportation Strategy

Transportation decisons should not be based solely on shipping cost because the cost differences between Air, Rail and Road are relatively small.

A more practical strategy woukd be to use:

. Road where operationally feasible
. Rail for steady bulk replenishment
. Air for urgent stockout prevention or high-margin products.

Greater cost-saving opportunities may comes from supplier and route negotiations rather than simply changing transportation modes.

# Recommended Action Priorities
Priority             Action                                                                Expected Benefit
Immediate            Replenish stockout-risky SKUs                                         Reduce lost sales and emergency replenishment
Immediate            Address Supplier 1 and Supplier 3 quality issues                      Reduce defects, returns, and complaints
Near Term            Increase appropriate use of Route 8                                   Reduce freight costs and lead times
Near Term            Improve Supplier 4 lead time and renegotiate Supplier 5 freight       Improve reliability and reduce costs
Monthly              Review SKU-level profitability                                        Improve product mix and operating margin

# Business Impact
Implementing these recommendations can help Uniquexcel:
. Reduce product stockouts
. Improve inventory availability
. Reduce supplier-related defects
. Improve supplier accountability
. Reduce unnecessary logistics costs
. Improve supply chian reliability
. Prioritize high-profit products
. Support better data-driven decision-making
. Improve overall operating profitability

# Conclusion
This project demonstrates how Excel can be used to transform raw supply chain data into actionable business insights.

By combining data cleaning, PivotTables, KPI analysis, visualization, and dashboard development, the project identified key risks related to inventory, suppliers, quality, logistics, and product profitability.

Most importantly, the analysis translates these findings into practical recommendations that management can use to improve supply chain performance and profitability.

# Author
Uchechi Amadi

Data Analytics Project |Supply Chain Analysis | Microsoft Excel


   
