
# 🚗 Indian Electric Vehicle Analysis using SQL and Power BI for AtliQ Motors
**Electric vehicle analysis of Indian market with real world data**
<br>
<br>
<img src = "https://github.com/user-attachments/assets/bffb5fa0-04aa-42d7-bf97-5d93b6659de1" width="600" height="350"/>


## **Important Links**
### [YOUTUBE VIDEO](https://youtu.be/iBr0Kh3lyes)
### [LINKEDIN POST](https://www.linkedin.com/posts/amaresam-sai-bharath-chand-47ba50168_hello-my-awesome-%F0%9D%90%8B%F0%9D%90%A2%F0%9D%90%A7%F0%9D%90%A4%F0%9D%90%9E%F0%9D%90%9D%F0%9D%90%88%F0%9D%90%A7-network-activity-7249829602448056320-hq3X?utm_source=share&utm_medium=member_desktop)
### [LIVE DASHBOARD](https://app.powerbi.com/view?r=eyJrIjoiN2RhNTIxNGItN2VhMS00ZWQ4LWE5NzgtY2UxOGMyZjBhY2NmIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&embedImagePlaceholder=true&pageName=799bc3e05d581d757123)
### [PRESENTATION WITH SQL CODES](https://drive.google.com/file/d/1XscLTMeExkzovQvg7OF3MlfqxtRyLIrD/view?usp=sharing)


## **Problem Statement**

AtliQ Motors, a leading automotive company, is planning to launch a new electric vehicle (EV) manufacturing plant in India. To make an informed decision, a comprehensive analysis was conducted focusing on key factors such as EV sales, market penetration, customer preferences, government incentives, and infrastructure availability across different states in India. The analysis aimed to identify the ideal state for setting up the plant, understand the dynamics driving EV adoption, and provide actionable recommendations for the company.

## **Research Questions**

### **Primary Research Questions:**

1. **Top 3 and Bottom 3 Makers (2023 and 2024):**
   - **Objective**: Identify the top 3 and bottom 3 makers in terms of the number of 2-wheelers sold.
   - **Analysis**: Using SQL, we employed window functions to rank makers by sales and identified the leaders and laggards for both years.

2. **Top 5 States by EV Penetration (2024):**
   - **Objective**: Identify the top 5 states with the highest penetration rates for 2-wheeler and 4-wheeler EVs.
   - **Analysis**: We calculated penetration rates using the formula `(EV Sales / Total Vehicle Sales) * 100` and identified states with the highest adoption rates.

3. **States with Negative Penetration (2022-2024):**
   - **Objective**: List states that experienced a decline in EV penetration from 2022 to 2024.
   - **Analysis**: We compared the penetration rates over the years and identified states with negative growth.

4. **Quarterly Sales Trends (2022-2024):**
   - **Objective**: Analyze quarterly sales trends for the top 5 EV makers (4-wheelers).
   - **Analysis**: By grouping data quarterly, we visualized the sales trends in Power BI, revealing seasonal patterns and growth trajectories.

5. **Comparison of EV Sales and Penetration: Delhi vs. Karnataka (2024):**
   - **Objective**: Compare EV sales and penetration rates between Delhi and Karnataka.
   - **Analysis**: We used SQL to extract and compare data, highlighting differences in market dynamics between the two states.

6. **CAGR in 4-Wheeler Units for Top 5 Makers (2022-2024):**
   - **Objective**: Calculate the Compound Annual Growth Rate (CAGR) for the top 5 makers in 4-wheeler units.
   - **Analysis**: We utilized SQL to calculate CAGR, showing which makers are growing the fastest.

7. **Top 10 States by CAGR in Total Vehicles (2022-2024):**
   - **Objective**: Identify the top 10 states with the highest CAGR in total vehicles sold.
   - **Analysis**: States with the fastest-growing vehicle markets were identified, highlighting regions with the greatest potential.

8. **Peak and Low Season for EV Sales (2022-2024):**
   - **Objective**: Determine the peak and low season months for EV sales.
   - **Analysis**: Monthly sales data was analyzed to identify seasonal trends, helping in inventory and marketing planning.

9. **Projected EV Sales in 2030:**
   - **Objective**: Project the number of EV sales in 2030 for the top 10 states by penetration rate.
   - **Analysis**: Using CAGR, we forecasted future sales, providing insights into long-term market potential.

10. **Revenue Growth Rate Estimation (2022-2024):**
    - **Objective**: Estimate the revenue growth rate for 4-wheeler and 2-wheeler EVs.
    - **Analysis**: Revenue growth was calculated assuming average unit prices, showing financial performance over the years.

### **Secondary Research Questions:**

1. **Primary Reasons for Choosing 4-Wheeler EVs (2023-2024):**
   - **Objective**: Understand the main reasons behind customers opting for 4-wheeler EVs.
   - **Analysis**: Factors like cost savings, environmental concerns, and government incentives were analyzed, with insights provided on consumer behavior.

2. **Impact of Government Incentives on EV Adoption:**
   - **Objective**: Analyze how government incentives and subsidies impact EV adoption rates.
   - **Analysis**: The role of state-specific incentives in driving EV sales was highlighted, showing which states are leading in providing support.

3. **Correlation Between Charging Infrastructure and EV Sales:**
   - **Objective**: Examine the relationship between charging infrastructure availability and EV sales/penetration rates.
   - **Analysis**: A strong correlation was found, emphasizing the importance of infrastructure in boosting EV adoption.

4. **Brand Ambassador for AtliQ Motors:**
   - **Objective**: Recommend an ideal brand ambassador for AtliQ Motors' EV/Hybrid vehicles.
   - **Analysis**: The concept of representing the common man was suggested, promoting inclusivity and accessibility.

5. **Ideal State for Manufacturing Plant:**
   - **Objective**: Identify the best state to start the EV manufacturing unit.
   - **Analysis**: Maharashtra, Tamil Nadu, and Gujarat were recommended based on subsidies, ease of doing business, and governance stability.

6. **Top 3 Recommendations for AtliQ Motors:**
   - **Objective**: Provide actionable recommendations for AtliQ Motors.
   - **Analysis**: Recommendations included selecting Maharashtra for the plant, investing in charging infrastructure, and focusing on inclusive branding strategies.

## **Technical Implementation**

The analysis was conducted using SQL for data extraction, transformation, and analysis, while Power BI was utilized for visualization. Key SQL techniques used include:

- **Window Functions**: For ranking and calculating metrics like CAGR and penetration rates.
- **Common Table Expressions (CTEs)**: To break down complex queries into manageable parts.
- **Stored Procedures**: To automate and streamline analysis tasks.
- **ER Diagram**: Used to establish relation between the tables

## **Visualizations**

Power BI was used to create interactive visualizations that provided insights into:

- Sales trends and seasonal patterns.
- State-wise EV penetration and adoption rates etc

<img src = "https://github.com/user-attachments/assets/fcdabc17-a285-4190-ba1f-d0a74e694225" width="600" height="350"/>
<img src = "https://github.com/user-attachments/assets/615db59a-e713-4669-bd98-78ea20721eaf" width="600" height="350"/>


## **Conclusion**

This analysis provides a comprehensive data-driven approach to understanding the EV market in India, offering valuable insights that can guide AtliQ Motors in their strategic decision-making as they plan to establish a new manufacturing plant. The use of advanced SQL techniques combined with Power BI visualizations has enabled a deep dive into the data, uncovering trends and opportunities that can drive future growth.

## **credits**

The dataset is taken from the Vahan Sewa. Thanks to the Vahan Sewa for 
providing datasets for public access which is a great learning asset - feel free to explore 
them here: [Vahan seva](https://vahan.parivahan.gov.in/vahan4dashboard/vahan/view/reportview.xhtml)

This project is part of code basics [resume challenge 12](https://codebasics.io/challenge/codebasics-resume-project-challenge)
Big thanks to Dhaval Patel Sir, Hemanand Vadivel Sir, and the entire Codebasics team for their invaluable guidance throughout this journey!

<br>
<br>
<br>

# Hi, I'm Bharath! 👋

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://codebasics.io/portfolio/Amaresam-Sai-Bharath-Chand)
&emsp;
[![Gmail](https://img.shields.io/badge/bharath.temp3@gmail.com-white?logo=Gmail)](mailto:bharath.temp3@gmail.com)
&emsp;
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amaresam-sai-bharath-chand-47ba50168/)
&emsp;
[![youtube](https://img.shields.io/badge/youtube-1DA1F2?style=for-the-badge&logo=youtube&logoColor=red)](https://youtu.be/ZkzLYNFPqwk)
&emsp;






