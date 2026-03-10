# Online_Retail_Analysis
Online Retail Customer Segmentation &amp; Customer Lifetime Value (CLV) Analysis 



1. Project Overview 
This project analyzes customer purchasing behavior using an online retail transaction 
dataset. The objective is to identify high-value customers, segment them based on 
purchasing patterns, estimate their Customer Lifetime Value (CLV), and provide actionable 
business insights. The analysis helps businesses understand customer behavior, improve 
retention strategies, and maximize revenue through targeted marketing initiatives. 
2. Project Objectives 
The main objectives of this project are: 
• Analyze customer purchasing behavior using transaction data 
• Create RFM metrics (Recency, Frequency, Monetary) for each customer 
• Segment customers into meaningful groups using clustering techniques 
• Estimate Customer Lifetime Value (CLV) for each customer 
• Identify high-value customers and customers at risk of churn 
• Perform revenue contribution and Pareto analysis 
• Develop an interactive Power BI dashboard to visualize insights 
3. Dataset Description 
The dataset contains transactional data from an online retail store. 
Key variables include: 
Column 
Description 
InvoiceNo 
Unique order identifier 
StockCode 
Product identifier 
Description 
Quantity 
Product name 
Number of items purchased 
InvoiceDate 
Date of purchase 
UnitPrice 
Price per unit 
CustomerID Unique identifier for each customer 
Column 
Country 
Description 
Customer's country 
A new column TotalPrice was created: 
TotalPrice = Quantity × UnitPrice 
This represents the total revenue generated per transaction. 
4. Tools & Technologies Used 
Programming & Analysis 
• Python 
• Pandas 
• NumPy 
• Scikit-learn 
Data Visualization 
• Matplotlib 
• Seaborn 
• Power BI 
Techniques Applied 
• Data Cleaning 
• Exploratory Data Analysis (EDA) 
• RFM Analysis 
• K-Means Clustering 
• Customer Lifetime Value Estimation 
• Pareto Analysis (80/20 Rule) 
5. Project Workflow 
Step 1: Data Cleaning 
The dataset was cleaned to ensure reliable analysis. 
Actions performed: 
• Removed missing CustomerID values 
• Removed cancelled transactions (Invoice numbers starting with “C”) 
• Removed negative quantity values 
• Converted date columns to datetime format 
• Created TotalPrice column 
Step 2: Exploratory Data Analysis (EDA) 
EDA was conducted to understand overall sales patterns and customer behavior. 
Key analysis included: 
• Monthly sales trends 
• Top revenue-generating countries 
• Best-selling products 
• Distribution of order values 
• Revenue per customer 
• Number of repeat customers 
EDA helped uncover patterns that guided further analysis. 
Step 3: RFM Analysis 
RFM analysis evaluates customer behavior based on three metrics: 
Recency – How recently the customer made a purchase 
Frequency – How often the customer makes purchases 
Monetary – How much money the customer spends 
Customers were scored using quintiles (1–5) to quantify engagement levels. 
Higher scores represent more valuable customers. 
Step 4: Customer Segmentation 
K-Means clustering was applied to segment customers based on RFM metrics. 
Customers were grouped into the following segments: 
• Champions 
• Loyal Customers 
• Potential Loyalists 
• At-Risk Customers 
• Lost Customers 
These segments represent different levels of engagement and value. 
Step 5: Customer Lifetime Value (CLV) Analysis 
Customer Lifetime Value was estimated to understand the long-term revenue potential of 
customers. 
CLV Formula: 
CLV = Average Order Value × Purchase Frequency 
Customers were categorized into three groups: 
• High CLV 
• Medium CLV 
• Low CLV 
This classification helps prioritize marketing and retention efforts. 
Step 6: Revenue Contribution & Pareto Analysis 
Revenue contribution analysis was conducted to determine which customers generate the 
most revenue. 
The Pareto principle was applied: 
Approximately 20% of customers contribute around 80% of total revenue. 
This insight highlights the importance of retaining high-value customers. 
6. Power BI Dashboard 
An interactive dashboard was developed to visualize customer insights. 
The dashboard includes: 
• Total Revenue 
• Total Customers 
• Average Customer Lifetime Value 
• Average Purchase Frequency 
• Customer Segment Distribution 
• Revenue Contribution by Segment 
• CLV Distribution 
• Customer Behavior Analysis (Recency vs Frequency vs Spending) 
The dashboard enables stakeholders to quickly understand customer behavior and make 
informed decisions. 
7. Key Insights 
• A small percentage of customers generate a significant portion of total revenue. 
• Champions and Loyal Customers contribute the largest share of revenue. 
• Many customers fall into the Potential Loyalists segment, indicating growth opportunities. 
• At-Risk customers show declining purchase activity and require re-engagement strategies. 
• High CLV customers represent the core value of the business. 
8. Business Recommendations 
1. Retain High-Value Customers (Champions) 
Champions are the most valuable customers. 
Recommended actions: 
• Provide loyalty rewards and exclusive discounts 
• Offer early access to new products 
• Introduce VIP membership programs 
Retaining these customers ensures stable long-term revenue. 
2. Strengthen Relationships with Loyal Customers 
Loyal customers purchase frequently but may spend less than champions. 
Recommended actions: 
• Offer personalized product recommendations 
• Introduce cross-selling and upselling strategies 
• Provide loyalty points and referral rewards 
This can increase their spending and move them into the Champion segment. 
3. Convert Potential Loyalists into Loyal Customers 
Potential Loyalists represent a large growth opportunity. 
Recommended actions: 
• Send targeted promotions after first purchases 
• Offer limited-time discounts to encourage repeat buying 
• Provide personalized marketing campaigns 
These strategies help convert occasional buyers into regular customers. 
4. Re-engage At-Risk Customers 
At-risk customers previously purchased frequently but have recently stopped buying. 
Recommended actions: 
• Send personalized re-engagement emails 
• Offer exclusive comeback discounts 
• Recommend products based on past purchases 
These campaigns can prevent customer churn. 
5. Win Back Lost Customers 
Lost customers have not purchased for a long time. 
Recommended actions: 
• Launch win-back marketing campaigns 
• Offer special promotional offers 
• Collect feedback to understand why they stopped purchasing 
Although recovery rates may be low, successful reactivation can increase revenue. 
9. Conclusion 
This project demonstrates how data analytics can help businesses understand customer 
behavior and improve decision-making. By applying RFM analysis, customer segmentation, 
and CLV estimation, businesses can identify their most valuable customers, optimize 
marketing strategies, and increase long-term profitability. 
The Power BI dashboard further enables stakeholders to monitor customer trends and 
revenue patterns through interactive visualizations. 
This end-to-end analytics workflow showcases practical data analysis techniques widely used 
in customer analytics and business intelligence.
