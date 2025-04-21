# Adventure-Works-Sales-Report
Created by: Ninh Phuong Hong

Contact: ninhphuonghong@gmail.com

LinkedIn: linkedin.com/in/hong-ninh

## Raw data
https://www.kaggle.com/datasets/abdallahprogrammer/adventure-works-microsoft-dataset

## About this report
This Power BI report analyzes historical Adventure Works sales data (Q3/2011 - Q2/2014) to evaluate sales performance, identify high-performing categories, and analyze sales trend. 

![image](https://github.com/user-attachments/assets/0f9fe2ac-7e88-4792-8ed4-d45560530105)

### Data Transformation using Power Query
Selected necessary columns for the report, renamed and filtered columns.

### Data Modelling
Table relationships were configured to develop data model. A calendar table was generated using DAX and marked as Date Table.

![image](https://github.com/user-attachments/assets/087a8b6c-dcd3-468e-8330-a31f6ef42cd2)

### DAX calculations
DAX was used to calculate total orders & sales measures, as well as assigning country name for online orders.

### Conditional formatting
Conditional formatting was used to adjust colors of bar chart, column chart and data bars in table.

![image](https://github.com/user-attachments/assets/77b38537-6e5f-46f6-a8f1-812aa001f50d)

### Visuals used as tooltip
A column named "ColorHexCode" was created to apply the correct colors to 2 visuals "Sales by Color" and "Order by Color", which were then used as tooltip for 2 bar charts.

![image](https://github.com/user-attachments/assets/72c83760-0909-4548-b9e5-91bcee87228d)

### Bookmark
Bookmarks were created for 2 states: the original state (the All bookmark), and for Europe countries within 2012 (the Europe 2012 bookmark), in order to quickly navigate to a specific stage of the report.

## Summary
Adventure Works Sales Data was cleaned and transformed to create visualizations that support company executives generating data-driven insights and decisions. Sales and Marketing team could focus on boosting sales for high-value categories such as bikes, together with promoting sales on dynamic online commerce platforms.
