# Saumya-Fashion-House-Annual-Sale-Report-2022

Analysis of Sales Report 2022 of Saumya Fashion House's using MS Excel and Drawing some useful insights for business Growth.

▶️Objectives of Project:
- To analyze the sales performance of Saumya Fashion House based on the sales data from 2022.
- To provide an annual report that aids in identifying areas of improvement and facilitates business growth in the upcoming years.
- To Answer few Questions asked by Trader from insight details.

▶️The Analysis involved the following process steps:
1. Data Cleaning: Ensuring data accuracy and consistency by removing any inconsistencies, errors, or duplicates.
2. Data Processing: Manipulating and transforming the sales data to prepare it for analysis.
3. Data Analysis: Applying statistical and analytical techniques to uncover meaningful patterns, trends, and insights.
4. Data Visualization: Presenting the analyzed data using charts, graphs, and visual representations to enhance understanding and interpretation.
5. Reports: Creating comprehensive reports summarizing the key findings and conclusions derived from the analysis.
6. Final Insights: Generating valuable insights and actionable recommendations based on the analysis results.

▶️Methodology involves here are:

1.Data gathering & cleaning: 
- Importing the CSV file having all the raw data into MS Excel.
- Performing operations to enhance data quality and consistency, such as:
  - Removing duplicate entries to ensure data integrity.
  - Correcting typo errors to improve accuracy.
  - Transforming the data into a more usable format or structure.
- Utilize utilities and tools within Excel to streamline and optimize data operations.
- Ensure that the data is clean, accurate, and ready for further analysis or processing.

2.Data Processing: 
- An Age group column was introduced in order to classify the Age column into three distinct categories, namely Senior (50 years and above), Adult (above 30 years), and Teenagers. This categorization was achieved through the utilization of the IF() function;
=IF(E2>=50,"senior",IF(E2>30,"adult","teeneger"))
- A new month column was established in order to obtain data categorized on a monthly basis, utilizing a dedicated function;
=TEXT(G2,"mmm")

3.Data Analysis using Pivot table:
- Developed a Clustered Combo-Line chart to effectively analyze the correlation between Orders and Sales on a monthly basis.
- Designed a Pie chart to visually represent the shopping distribution between Men and Women, providing insights into their respective percentages.
- Constructed a Bar chart displaying the Top 5 States with the highest sales, enabling quick identification of the regions with the most significant revenue generation.
- Generated a Pie chart illustrating the distribution of Order Status among customers, facilitating a comprehensive understanding of the various statuses.
- Developed a Column chart that depicts the purchasing patterns based on age groups for both Men and Women, providing valuable insights into their buying behaviour.
- Created a Pie chart to present the percentage share of each Distribution channel, enabling an understanding of the distribution channel preferences and their respective market shares.

🔰INSIGHTS DRAWN:
> Sale in Month of March is Highest
>	Overall Women are more likely to buy compared to Men (~64%)
>	Maharashtra, Karnataka and Utter Pradesh are among Top 3 states (~35%)
>	Adult age group (30- 49yrs) is max contributing (~50%)
>	Amazon, Flipkart and Myntra channels are max contributing (~80%)

🔰Final Conclusion to improve Saumya Fashion House Annual Sales:
> Target Women customers of age group (30-49 yrs) living in Maharashtra, Karnataka and Utter Pradesh By showing more Ads/Offers/Coupons available on Amazon, Flipkart and Myntra.

♻️Some other insights asked by Trader:
- 1)Q. Which month got the highest sales and orders?
- Ans- March Month has got the highest number of sales and orders.
- 2)Q. Who purchased more- men or women in 2022?
- Ans- Women are major buyers.
- 3)Q. What are different order status in 2022?
- Ans- Order Delivered, Refunded, Cancelled & Returned.
- 4)Q. List top 5 states contributing to the sales?
- Ans- Maharashtra>Karnataka> Telangana>Tamil Nadu>Kerala
- 5)Q. Which channel is contributing to maximum sales?
- Ans- Amazon followed by Flipkart. 
- 6)Q. Which Category got the highest sales? 
- Ans- Western wear
- 7)Q. What is the percentage of the orders that are cancelled and refunded? 
- Ans- Order Being Cancelled was 3% and Being got Returned was 2%.


