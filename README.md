# Excel Case Study: Customer Behavior Segmentation for a Telecom Company
## Business Problem
Our client is a telecom company that offers voice, 2G, 3G, and 4G data services. To improve their business strategy and customer retention, they have grouped users into four behavioral categories labeled A, B, C, and D, based on how they interact with the service after signing up and completing onboarding.
Category A: Customers who sign up and abandon the tool after onboarding.
Category B: Customers who use the service as a free user.
Category C: Customers who use free features and eventually upgrade to premium.
Category D: Customers who upgrade immediately and continue as business users.

## Client Objectives
- Understand how different features (like Age, Gender, Education, Income, Employment status, Tenure) influence customer behavior.
- Identify high-value customers and potential upgraders.
- Recognize early signs of churn or abandonment (Category A).
- Use segmentation insights to plan targeted marketing campaigns.
## Dataset Description
Columns:
Tenure - Number of months a customer has been active
Age - Customer’s age
Marital Status - Single or Married
Income - Annual income
Education Level - Level of education (e.g., Graduate, Post Graduate, Secondary)
No. of Years Employed - Employment experience in years
Retired or Not - Yes/No
Gender - Male or Female
Custcat - Customer category (A, B, C, D)

## Case Study Objectives
- Clean and transform data using Excel functions
- Build and analyze Pivot Tables and Charts
- Visualize trends using bar, line, and pie charts
- Build a customer segmentation dashboard
- Draw actionable insights for the client

### Part 1: Data Cleaning & Preparation
Tasks:
1. Add a new column: “High Income” with value “Yes” if Income > ₹80,000 else “No” using IF.
2. Classify employment status: Create a column “Experience Level”:
   - Senior if Years Employed ≥ 10
   - Mid if 5 ≤ Years Employed < 10
   - Junior if < 5
3. Add “Tenure Group”:
   - 0–12 months: New
   - 13–36 months: Experienced
   - 37+ months: Loyal
### Part 2: Pivot Table Analysis
Analysis Questions:

1. Count of customers in each Custcat.
2. Count of gender-wise customers in each Custcat.
3. Average Tenure, Income, and Age by Custcat.
4. Distribution of Education Level across categories.
5. Number of high-income customers by Custcat.
### Part 3: Visualization Tasks
Charts to Create:
1. Bar Chart – Customer count by Custcat.
2. Pie Chart – Gender distribution across all customers.
3. Clustered Bar Chart – Education level vs. Customer category.
4. Line Chart – Avg. Income vs. Custcat.
5. Radar Chart – Distribution of Age or Tenure.
6. Stacked Column – Experience Level vs Custcat.
### Part 4: Dashboard Creation
Instructions:
- Build a one-page dashboard using:
  - Pivot charts
  - Slicers for Gender, Education Level, and Tenure Group
  - KPIs:
    - Total Customers
    - % of High Income Customers
    - Avg. Tenure
    - Most common Education Level in Category C
- Add dynamic filtering using slicers
### Part 5: Final Analysis & Insights
Questions for Reflection:
1. Which category has the youngest average age?
2. What is the income profile of Category D users?
3. Does education level correlate with upgrading behavior (Category C or D)?
4. Recommend 2–3 target segments for a premium upgrade campaign.
5. What should the company do to retain Category A users?

