
# CUSTOMER-CHURN-ANALYSIS---POWER-BI-AND-EXCEL-PROJECT-
 Analyzed customer churn using Power BI, Power Query, DAX, and Excel/CSV. Cleaned and transformed data, built KPIs and interactive dashboards, and identified churn patterns across contract type, tenure, payment method, and monthly charges. Delivered actionable insights to improve customer retention and reduce churn.
 
## The dataset used
https://1drv.ms/x/c/B35DBD2D8A213BFB/IQDRFaSXvwEaT5i1tr6AJzkKAQ27YqqZ6tlq2YMA6j1-uIE?e=SaMUoS   

## Business Questions to solve 
1. What is the overall customer churn rate?
2. Which customer segments (contract type, tenure, payment method) churn the most?
3. Is there a relationship between monthly charges and churn?
4. Do newer customers churn more than long-tenured ones?
5. Which services (internet, streaming, tech support) correlate with higher/lower churn?
6. How much revenue is being lost to churn?
7. What's the churn trend over time (if date data is available)?
8. Does gender have any influence on customer churn?
9. Which contract type has the highest churn rate?
10. Which age group is most likely to churn?

## LINK TO FULL PROJECT
https://1drv.ms/b/c/B35DBD2D8A213BFB/IQAojGRG2CB1QrT9atcTrzf7ASFGBD01JytIwoFlwq_bqng?e=QBuOIX

## DASHBOARD INTERACTION LINK
https://1drv.ms/u/c/B35DBD2D8A213BFB/IQDKdQpP_m1NTa5z77j6MlRSAU2U8GFd83p7vxHWi3Lg8C4?e=a4lZCe

## PROJECT PROCESS

1. Understanding the Problem
Defined the business question: Which customers are churning, why, and what can be done to retain them?
Identified the target variable: Churn (Yes/No)
Identified key factors likely to influence churn: contract type, tenure, monthly charges, payment method, age, gender
2. Data Collection
Sourced the customer dataset containing demographic, billing, contract, and churn information
3. Cleaning the Dataset
Checked for missing, duplicate, and inconsistent values
Fixed data types (e.g., ensured numeric fields like MonthlyCharges and Tenure were correctly formatted)
Standardized categorical values (e.g., consistent labels for Gender, Contract Type, Payment Method)
Removed irrelevant or redundant columns not needed for analysis
4. Data Transformation
Created calculated columns/buckets for analysis: Tenure buckets, Monthly Charge buckets, Age Groups
Built a Risk Segment classification (High Risk / Low Risk) based on churn likelihood indicators
5. Building the Data Model
Structured the dataset in Power BI's data model
Verified relationships and data types were correctly set for accurate visual calculations
6. Writing DAX Measures
Created key measures: Total Customers, Churned Customers, Churn Rate, and segment-based counts
7. Designing the Dashboard
Built visuals to answer each business question: churn by gender, contract type, age group, tenure, monthly charges, and payment method
Added interactive slicers (Male/Female) to allow filtered views
Applied consistent color theming for clarity (orange/red for churn emphasis)
8. Analyzing the Results
Reviewed each visual to identify patterns and high-risk segments
Cross-checked findings across multiple charts to confirm consistency (e.g., tenure and contract type both pointing to new customers as high-risk)
9. Extracting Insights
Summarized key patterns driving churn (contract type, tenure, charges, payment method)
10. Formulating Recommendations
Translated insights into actionable business recommendations for reducing churn
11. Documentation & Sharing
Exported dashboard views and insights into a PDF report
Documented the project on GitHub with a README covering the business problem, tools used, process, KPIs, insights, and recommendations
Published the Power BI report for interactive viewing

## DASHBOARD IMAGES 
<img width="1324" height="622" alt="PJ PIC" src="https://github.com/user-attachments/assets/0dfaa4a4-254e-427d-bc27-e638cf2f8899" />
<img width="1968" height="1128" alt="MALE" src="https://github.com/user-attachments/assets/d476ffcb-4f4c-4bff-8d12-44f9744f1b86" /> 
<img width="1968" height="1128" alt="FEMALE" src="https://github.com/user-attachments/assets/37851bc3-0d3f-471c-bcf2-f33ec79336e2" />

## Conclusion

This project analyzed churn behavior across 178 customers to identify who is leaving, why they're leaving, and where the business should focus its retention efforts. The analysis revealed a clear and consistent pattern: churn in this customer base is not random — it is heavily concentrated among specific, identifiable segments. Customers on monthly contracts, those in their first ten months of tenure, and those paying higher monthly charges consistently showed the highest likelihood of churning. This tells a coherent story: newer customers on flexible, low-commitment plans are the most vulnerable to leaving, especially once billing costs rise.

The dashboard also surfaced a payment-method pattern worth investigating further — customers using UPI churned at a noticeably higher rate than those on Debit or Credit Card, suggesting the payment experience itself may be contributing to dissatisfaction or disengagement. Demographically, churn was fairly balanced between male and female customers, meaning gender is not a meaningful driver on its own — but middle-aged and senior customers churned more than younger customers, pointing to a need for age-tailored retention strategies rather than a one-size-fits-all approach.

Overall, with a 37% churn rate, more than one in three customers are at risk — a figure significant enough to justify immediate, targeted intervention rather than broad, generic retention campaigns.

## Key Insight

Churn in this business is a tenure and contract problem before it is anything else. The data shows that customers who are new and uncommitted (short tenure, monthly contracts) are the ones leaving — meaning the business's biggest opportunity isn't complex demographic targeting, but a simple structural fix: converting customers to longer contracts early and strengthening the first few months of the customer relationship. If the business acts on just two levers — improving early-tenure onboarding and incentivizing annual contracts — it directly addresses the two strongest churn drivers identified in this analysis, and stands to meaningfully reduce the 37% churn rate.
