# Atliq-Grands-Hospitality-Analysis-Python-Project

# Company Overview

AtliQ Grands is a leading hotel chain operating across major Indian cities like  Mumbai, Delhi, Bangalore, and Hyderabad, with diverse hotel types such as AtliQ Seasons, AtliQ Exotica, AtliQ Bay, and AtliQ Palace.
With over 20 years of experience in the hospitality industry, the company has recently faced declining revenue and market share, highlighting the need for data-driven strategies to enhance operational efficiency, maximize revenue, and maintain a competitive edge.

# Project Objective

The primary objective of this project is to leverage data analytics on historical booking records from both the official website and third-party platforms. By analyzing patterns in bookings, revenue, occupancy, and customer behavior, the project aims to:

- Identify high-performing and underperforming properties.
- Optimize revenue generation across platforms and cities.
- Inform strategic decision-making for marketing, pricing, and operational improvements.
- Provide actionable insights to drive growth and competitiveness in the market.


# Problem Statement
AtliQ Grands is facing declining revenue and market share across its hotels. The challenge is to analyze booking data from both official and third-party platforms to uncover insights, optimize revenue, and support data-driven decisions.


# Tools used

- Python (pandas,matplolib)
- Jupyter Notebook

# Datasets

- dim_date.csv
- dim_hotels.csv
- dim_rooms.csv
- fact_aggregated_bookings.csv
- fact_bookings.csv
- new_data_august.csv

# Methodology

- Dataset Review: Conducted a thorough examination of the dataset to understand its structure and identify inconsistencies or missing values.
- Invalid Data Correction: Corrected or removed erroneous entries, such as negative guest counts, to ensure data reliability.
- Outlier Handling: Detected and addressed outliers that could distort analysis.
- Created New Column: Added calculated fields, such as occupancy percentage (successful bookings divided by total capacity), to provide deeper insights into hotel performance.
- Validation: Verified the cleaned and enriched dataset for accuracy and readiness for further analysis.

Key Insights

- Room Class Performance:
     The Presidential Suite (RT4) commands premium pricing and records the highest occupancy rate at 59.3%, outperforming all other room categories.

- City-Level Occupancy:
    Delhi leads in average occupancy at 60.4%, while Bangalore lags behind at 55.3%, indicating potential for targeted interventions in underperforming cities.

- Weekend vs. Weekday Trends:
   Occupancy levels are consistently higher on weekends, suggesting an opportunity to implement dynamic pricing or weekend-focused promotions to maximize revenue.

- Monthly Performance:
   Occupancy peaked in June (Delhi at 60.4%), with Hyderabad following at 56.9%. Revenue was highest in May 2022 (₹408.4M), followed by July 2022 (₹389.9M), indicating seasonal demand patterns.

- City Revenue Contribution:
   Mumbai contributes the most to total revenue, generating ₹668.6M, emphasizing its critical role in the overall portfolio.

- Property-Level Revenue:
   AtliQ Exotica dominates with ₹219M, while AtliQ Seasons significantly underperforms at ~₹46M, revealing heavy dependence on top-performing properties and the need to uplift weaker assets.

- Customer Satisfaction:
   Delhi tops in customer satisfaction with an average rating of 3.78, whereas Bangalore (3.40) underperforms, highlighting areas for service improvement.

- Revenue by Booking Platform:
   The majority of revenue originates from “Others” (40.9%), followed by MakeMyTrip (19.8%), indicating opportunities to optimize partnerships and diversify platform strategies.


  






  
