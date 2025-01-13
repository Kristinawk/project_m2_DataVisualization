# project_m2_DataVisualization
Power BI Dashboard | Perfume Business Insights  
<img src="https://github.com/Kristinawk/project_m2_DataVisualization/blob/main/visualization/actionable%20insights.png" width="400" />

# Purpose
The outcome of this project is an interactive Dashboard intended to deliver actionable insights to the business. It is about Perfume Worldwide Enterprise and the target audience are Sales Director and Region/Store Sales Managers; Product/Promotion Managers; Marketing Managers; and Customer Relationships Manager.  

The Dashboard is developed in **Power BI**. The dataset has been tailored for this use case. The Dashboard is the result of combining different data tables into a normalized [data model](https://github.com/Kristinawk/project_m2_DataVisualization/blob/main/data/Data%20model.png) that fits the pre-defined [functional design mockup](https://github.com/Kristinawk/project_m2_DataVisualization/blob/main/visualization/functional%20design%20mockup.png).  

The Dashboard shows three sets of KPIs: Order counting, Turnover/Discounts and Customer data. The Order Counting aims to explain how the value is generated from Visits to Orders. The Order Value is discomposed into _(Visits * Conversion Rate) * Average Order Value_, where Conversion Rate is a ratio of Orders by Visits. This allows identifying growth levers and take action. All metrics are dynamic and can be filtered by period and region/store. Additionally, all KPIs are compared to last year to give context to the data.

# Data
The dataset consists of csv files. You can find all data tables [here](https://github.com/Kristinawk/project_m2_DataVisualization/tree/main/data).

# Insights

* **Order counting**: 
Visits, Conversion Rate and Average Order Value are growth drivers for Order Value. The Dashboard shows a decrease in Visits and Conversion Rate. By contrast, Average Order value has increased but not enough to compensate the negative impact of the other two levers. This gives a "call to action" to Commercial and Marketing departments. With proper context in mind (e.g. price strategy, customer behaviour, etc.) they need to turn around the negative trend.

* **Turnover**:
One of the aims of the business is to increase the top-line. This why it is crucial to monitor the Turnover. The Dashboard shows that in current year the Turnover is equal to last year. If there are growth or expansion plans in the organization, it might be not an expected result. The business usually has the right context to interpret the results and act in consequence. The Dashboard provides all necessary details (month, region, store, product...) in a user-friendly and efficient way.

* **Discounts**:
Discounts are used as a tool to drive visits, increase sales and keep stock levels under control. But they need to be well-disgned and balanced as they also decrease gross profit. The Dashboard shows what promotion types are the most used and their Discount Value as percentage of Turnover. If Discount percentage is too high, it might be an indicator of a non-profitable promotion.

* **Product Mix**:
Right product offer is the key to success. Therefore it is crucial to have a good understanding of product mix and best sellers. This affects not only Commercial deparments but also the whole Supply Chain. The Dashboard shows that some product categories with high business share are decreasing vs last year. The business should concentrate their efforts into solving this.

* **Customers**:
Understand customer profile and satisfaction is important across different business areas. Customer should be in the center of key business decisions, from product mix and marketing campaigns to customer service. Membership programs provide customers data. The Dashboard shows that 50% of Members are Women between 30 and 75 years old and men between 30 and 45. It also indicates that the Net Promoter Score is relatively low, especially for certain customer profiles.

In summary, the Dashboard shows some points of attention that require immediate action: visits and conversion rate are falling, some key product categories are decreasing, customer satisfaction is not guaranteed and, finally, growth target and/or expansion plans need to be revised and reinforced in the organization.

# Built With
DBdiagram - for data model mockup  
Excalidraw - for functional design mockup  
Power BI Desktop - for data model development and BI Dashboard  
Python - for data exploration and data quality check

# Usage
Ensure Power BI Desktop is installed. Access the dashboard [here](https://github.com/Kristinawk/project_m2_DataVisualization/blob/main/visualization/Project_m2_powerBI.pbix).

# Folders structure
└──  project_m2_DataVisualization  
│  
│   .gitignore  
│   README.md  
│  
├───archive  
│  
├───data  <div style="padding-left: 60px;">
│       Customers_Table.csv  
│       Data model.png  
│       Date_Table.csv  
│       Marketing_Campaigns_Table.csv  
│       Orders_Table.csv  
│       Products_Table.csv  
│       Promotions_Table.csv  
│       Stock_Table.csv  
│       Stores_Table.csv  
│       Visits_Table.csv  
│       Weather_Table.csv  
│       Working_Hours_Table.csv  </div>
│  
├───notebooks  <div style="padding-left: 60px;">
│       data_cleaning&manipulation.ipynb  
│       data_exploration.ipynb  </div>
│  
└───visualization  <div style="padding-left: 60px;">
│       actionable insights.png  
│       Project_m2_powerBI.pbix  
│       functional design mokcup.png </div> 


