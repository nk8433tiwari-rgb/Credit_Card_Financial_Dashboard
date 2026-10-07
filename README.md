Credit Card Financial & Customer Analytics Dashboard 

Project Objective To develop a comprehensive weekly credit card dashboard that provides real-time insights into key performance metrics and operational trends.
This enables stakeholders to effectively monitor, analyze, and optimize credit card operations, revenue growth, customer segmentation, and risk exposure.   

Data Pipeline & Execution Steps
1. Data Import & Modeling
Database Setup : PostgreSQL database setup containing customer and transaction data ( cust_detail, cc_detail).

Data Integration : Imported transactional ( cc_add.csv, credit_card.csv) and demographic datasets into Power BI via SQL queries.

Data Transformation : Cleaned data types, handled missing values, and created standardized date fields for weekly rollups.

2. DAX Calculations & Measurement Engineering
Custom DAX measures were constructed to segment demographics, compute weekly revenue, and compare performance WoW (Week-over-Week):
Customer Age Group Segmentation :   

Dashboard VisualizationCredit Card Transaction Report : 
Highlights high-level KPIs, quarterly revenue trends, swipe vs. online vs. chip payment channel usage, and spending categories. 
Credit Card Customer Report : Visualizes customer lifetime value, income groups, education levels, job types, age brackets, and top geographic distributions.   

Key Performance Insights
YTD Overview PerformanceTotal 
Revenue : $57M   
Total Interest Earned : $8M   
Total Transaction Volume : $45.5M 
across 667.2K transactions   
Customer Income Sum : $588M   
Average Customer Satisfaction Score (CSS) : 3.19  
Portfolio Health : 57.5% Activation Rate | 6.06% Delinquency Rate

Key Segment BreakdownCard 
Category Dominance : Blue & Silver cards drive 93% of overall transactions, generating $47M and $6M respectively. 
Demographics & Gender : Male customers lead overall revenue contribution with $31M , while female customers generate $26M.
The 40–50 age group is the top contributing cohort ($25M total).  
Geographic Concentration : Top 3 states— Texas (TX), New York (NY), and California (CA) —account for 68% of total revenue.  
Job Profile : Business owners/businessmen generate the highest revenue ( $17.7M ), followed by white-collar workers ( $10.3M ).   
Payment Method Choice : Swipe transactions lead with $36M , followed by Chip ($17M) and Online ($4M).   
Expenditure Categories : Bills ($14M), Entertainment ($10M), and Fuel ($10M) represent the largest spend sectors.   
