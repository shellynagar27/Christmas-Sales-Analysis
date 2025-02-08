# Christmas Sales Analysis

## Overview
This project was created as part of the **FP20 Analytics December 2024 Challenge**. It analyzes consumer behavior and sales trends during the Christmas season, leveraging **Power BI for visualization, Python and Power Query for exploratory data analysis (EDA), and Figma for UX design**. Freepik and Flaticon were used for icons.

## Live Dashboard
[View Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMjgxMDU2MmItYzczZS00YWRhLWE3MGYtNjNjNzEzOWQ0N2E5IiwidCI6IjQ2NTRiNmYxLTBlNDctNDU3OS1hOGExLTAyZmU5ZDk0M2M3YiIsImMiOjl9)

## LinkedIn Post
[View on LinkedIn](https://www.linkedin.com/feed/update/urn:li:groupPost:12751070-7277576964494811136/)

## Dataset
The dataset originates from a leading market research firm that collected detailed data on holiday sales, including customer demographics, purchase behaviors, promotional effectiveness, and satisfaction metrics. 

The objective of this analysis is to uncover insights into consumer shopping habits during Christmas, explore the impact of promotions, identify key drivers of satisfaction, and optimize future holiday strategies.

## Data Preparation
The dataset comprises two tables:
- **Main Dataset** – Contains transactional and customer-related data
- **Data Dictionary** – Provides metadata descriptions for the dataset

Additionally, the following supplementary tables were created to enhance analysis:
- **Measure Table** – Stores all calculated measures
- **Dim_Date Table** – For date-based analysis
- **Time Bin Table** – Categorizes time into Morning, Late Morning, Afternoon, Evening, and Night

## Data Model-
![Screenshot 2025-02-08 181516](https://github.com/user-attachments/assets/95096c90-ae3f-4360-9832-50fe8aa839da)

## Steps Taken
1. **Data Exploration** – Understanding dataset structure and contents
2. **Data Cleaning** – Removing extra whitespaces and duplicates
3. **Data Transformation & Formatting** – Ensuring proper data types, creating the Dim_Date table
4. **Data Modeling** – Establishing relationships between Fact Table and Dim_Date table
5. **Measure Creation & Visualization** – Developing necessary metrics and dashboards to address key questions
6. **Interactivity Enhancements** – Adding slicers for better user control, including a restore button
7. **Navigation & Usability** – Creating an information page to guide users through charts and filters

## Key Questions Addressed
This Power BI report aims to answer the following questions:

1. **Sales Volume Trends:**
   - During Black Friday, more sales occurred compared to Christmas from 2018 to 2023.
   - Black Friday sales range from **2.06K to 2.19K**, while Christmas sales range from **1.37K to 1.59K**.

2. **Customer Demographics:**
   - **Gender Distribution:** Nearly uniform distribution across genders.
   - **Age Breakdown:**
     - Female: Majority from **25-34, 45-54, and 55-64 (53%)**; least from **65-70 (11.7%)**.
     - Male: Majority from **55-64, 25-34, and 35-44 (58%)**; least from **65-70 (10%)**.
     - Others: Majority from **45-54, 25-34, and 35-44 (57%)**; least from **65-70 (11%)**.
     - **Overall:** Most customers are from the **25-34** age group, least from **65-70**.

3. **Regional Sales Trends:**
   - **Highest total orders:** British Columbia (**818**), Northwest Territories (**716**)
   - **Lowest total orders:** Prince Edward Island (**609**), Newfoundland and Labrador (**614**)

4. **Promotional Impact on Sales:**
   - Promotions have minimal effect on total Christmas sales volume.

5. **Popular Products & Preferences:**
   - **Overall:** Electronics and Toys sell slightly more than Food, Clothing, and Decorations.
   - **By Age Group:**
     - **18-24:** Most bought: Electronics | Least bought: Clothing
     - **25-34:** Most bought: Electronics & Toys | Least bought: Food
     - **35-44:** Most bought: Electronics | Least bought: Decorations
     - **45-54:** Most bought: Toys | Least bought: Decorations
     - **55-64:** Most bought: Clothing | Least bought: Food
     - **65-70:** Most bought: Decorations | Least bought: Electronics
   - **By Gender:**
     - Male: Most bought: Electronics | Least bought: Food
     - Female: Most bought: Food | Least bought: Clothing
     - Others: Most bought: Toys | Least bought: Electronics
   - **By Location:**
     - Ontario: Most bought: Electronics | Least bought: Toys & Clothing
     - British Columbia: Most bought: Toys & Clothing | Least bought: Food
     - Quebec: Most bought: Toys | Least bought: Electronics
     - Alberta: Most bought: Clothing | Least bought: Decorations
     - *More regional breakdowns available in the report.*

6. **Customer Satisfaction Scores:**
   - Christmas avg score: **2.97**
   - Black Friday avg score: **2.99**

7. **Gift Wrapping Usage:**
   - **Total Christmas Orders:** **2,908**
   - **Gift-wrapped Orders:** **1.48K**
   - **Highest Gift Wrap Orders:** British Columbia (**137**)
   - **Lowest Gift Wrap Orders:** Nova Scotia (**102**)

8. **Shipping & Delivery Trends:**
   - **Shipping Method Preferences:**
     - **Overnight:** **34%** | **Standard:** **33%** | **Express:** Remaining
     - No strong preference for shipping method during Christmas.
   - **Delivery Time vs. Satisfaction:**
     - No major correlation between delivery time and satisfaction.
     - Example: Avg satisfaction **~2.98** for **1-day delivery**, **2.96** for **2-day delivery**, **3.06** for **4-day delivery**.
   - **Weather Effects on Delivery Time:**
     - 1-day delivery: Mix of rainy, snowy, and sunny days.
     - 3-day delivery: More sunny days.
     - 4-day delivery: More snowy days.
     - 5-day delivery: More rainy and snowy days.

9. **Product Returns Analysis:**
   - **Total Christmas Returns:** **1,277**
   - **Weather impact on returns:**
     - **Rainy:** 502 returns (Toys, Decorations, Food most returned)
     - **Sunny:** 450 returns (Electronics, Food, Decorations most returned)
     - **Snowy:** Remaining returns (Clothing, Decorations most returned)
   - No major effect of customer satisfaction or delivery time on returns.

10. **Weather & Event Influence on Sales & Satisfaction:**
   - **Sales Volume by Weather:**
     - Rainy Days: **10,353** | Avg Satisfaction: **2.97**
     - Snowy Days: **10,016** | Avg Satisfaction: **2.97**
     - Sunny Days: **9,737** | Avg Satisfaction: **3.01**
   - **Event-Based Sales:**
     - Christmas Total Sales: **8.75K** | Avg Satisfaction: **2.97**
     - Black Friday Total Sales: **12.70K** | Avg Satisfaction: **2.99**

## Conclusion
This analysis reveals that while Christmas sales are strong, Black Friday consistently outperforms Christmas in total sales. Age, gender, and location influence product preferences, with Electronics and Toys being the most popular. Promotions have little impact on boosting sales, and shipping methods do not significantly affect customer satisfaction. Returns are fairly distributed across different weather conditions, with Toys, Electronics, and Clothing being the most frequently returned. To improve holiday sales, businesses should focus on personalized promotions, better regional marketing, and enhancing customer experience rather than relying solely on discounts. 🚀

---

For more details, feel free to explore the repository and interact with the Power BI dashboard.

🚀 Happy Analyzing!

- - - 
## Future Enhancement
Planning to improve the dashboard for better clarity and insights.
