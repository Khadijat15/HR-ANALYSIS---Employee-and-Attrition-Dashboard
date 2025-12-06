# HR Analytics Dahboard - Performance and Attrition Prediction
Developed interactive Power BI dashboards that analyse employee performance and attrition trends, with predictive analytics to identify high-risk employees.

# 🌼Purpose
To explored the relationship between performance ratings, salary bands, job roles, demographics, and attrition. Using Power BI (Key Influencers, Decomposition Tree, Trend Analysis), the goal was to identify the underlying drivers of employee exits and provide data-driven recommendations for retention.


# 🗃️ Data Preparation
I used power query to clean the data
   - Renaming and formatting in consistent columns.
   - Checking for duplicates.
   - Creating new columns, such as Employee Age.
   - Using conditional columns and DAX to derive additional metrics.
   - Categorizing employees using salary band and Age band.

  # ✂️Tools Used
  - Power BI
  - DAX

 
   # ? Key Questions
   Core Analytical Questions
    - Do low-paid employees tend to leave more?
    - Does department or job role affect attrition?
    - Do age and marital status influence attrition?
    - Does performance score affect employee retention?
    - Who are the top-performing or low-performing employees?
    - Which department and managers are performing well?
    
# 🔍 Key Findings
  Performance & Attrition
 - Employees on PIP or rated “Needs Improvement” recorded the highest attrition rates.
 - Most of these employees were in the lowest salary bands, suggesting dissatisfaction linked to pay.
 - Despite some low performers, overall performance distribution was strong:
 - 78% — Fully Exceeds Expectations
 - 12% — Exceeds Expectations
 - 6% — Needs Improvement
 - 4% — PIP

Salary Band Analysis
 - Low salary earners showed the highest likelihood of leaving.
 - The upper-mid salary band (#100,000–#120,000) also had high attrition despite high performance.
 - Further investigation revealed reasons such as:
 - Career change.
 - Internal department transfers.
 - Unreported exits (no formal communication).
 - Employees in this salary category were mostly aged 36–50, with 50+ employees showing increased attrition tendencies.

Department & Job Role Insights
 - The Production Department recorded the highest attrition rate.
 - Roles like Production Technician I & II had the strongest likelihood of leaving.
 - These roles fall into the lower salary bands, linking job role → salary → attrition.
 - Despite high attrition, production also had the highest number of top performers, indicating a retention problem, not a performance problem.

 # 📊 Predictive Analytics
      Used Key Influencers, Decomposition Tree, and Trend Analysis in Power BI.

 Trends Over Time
 - Attrition showed no monthly or seasonal variation.
 - Attrition remained constant over the years.

Key Influencers
 - Department (Production) → 1.93x more likely to leave.
 - Marital Status (Divorced) → 1.70x more likely to leave.
 - Job Role (Production Technician II) → 1.49x more likely to leave.
 - Salary Band (Low) → strongest likelihood of leaving.

Decomposition Tree Findings
 - Low-salaried employees = highest attrition contributors.
 - Production job roles = major drivers of attrition.
 - Salary adjustments could reduce attrition significantly.

# 📌 Conclusion
 - Attrition is heavily influenced by salary level, job role, and performance issues.
 - Production workers, especially technicians, are at high risk of turnover.
 - Older employees and certain demographics (e.g., divorced employees) show higher exit tendencies.
 - Some high-performing employees leave due to career or personal factors, not salary.
 - Predictive analytics confirms that salary reviews, targeted retention strategies, and improved support systems can help reduce attrition.

# ✔️ Recommendations
 Salary & Compensation
 - Review and increase lower salary bands, especially in production roles.
 - Reassess #100,000–#120,000 salary band to ensure competitiveness for mid-career employees.

Retention Programs
 - Develop targeted retention strategies for Production Technicians I & II.
 - Create clear career paths, training opportunities, and incentive structures.

Improve PIP Support
 - Offer skill-building programs, coaching, and mentoring for PIP employees.
 - Strengthen performance feedback processes to reduce performance-related exits.

Address Non-Salary Attrition Drivers
 - Track internal transfers and unreported exits more effectively.
 - Conduct engagement surveys and exit interviews to understand deeper reasons behind turnover.

Monitor High Performers
 - Provide recognition, career development plans, and leadership pathways.
 - Prevent loss of top performers due to career change or internal movement.

# 📁 Files / links
 - This file - README.md
 - Power BI dashboard - Employee attrition, performance and predictive analysis file
 - You can also check my article on medium - https://medium.com/@omowunmikhadijat011/behind-the-metrics-predicting-attrition-with-power-bi-0b00a0122a41
 
