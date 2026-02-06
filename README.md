# Customer Churn Analysis — Telecom Industry

## Project Overview
This project analyzes customer churn behavior within a telecom subscription business to identify high-risk segments and key retention drivers. By leveraging exploratory data analysis (EDA) and visualization, the goal is to translate raw data into actionable business strategies to improve customer lifetime value.

## Objectives
* **Identify Patterns:** Understand overall churn distribution across the dataset.
* **Pinpoint Drivers:** Determine the key factors (contract type, tenure, etc.) influencing customer exit.
* **Customer Segmentation:** Isolate high-risk cohorts for targeted intervention.
* **Strategic Recommendations:** Propose data-driven retention strategies for stakeholders.

## Dataset
* **Source:** Telecom customer dataset (~7,000 records).
* **Features:**
    * **Demographics:** Gender, age range, and partner/dependent status.
    * **Service Usage:** Phone service, multiple lines, internet service (DSL/Fiber optic).
    * **Contract Details:** Contract type, paperless billing, and payment method.
    * **Financials:** Monthly charges and total charges.
    * **Target:** Churn status (Yes/No).

## Tools & Technologies
* **Language:** Python
* **Libraries:** Pandas, NumPy, Plotly (Interactive Visualizations)
* **Environment:** Jupyter Notebook

## Key Insights
* **The "Danger Zone":** Churn is highest within the first **12 months** of tenure.
* **Contract Influence:** Month-to-month contracts are the strongest predictor of churn; long-term contracts significantly improve stability.
* **Pricing Pressure:** Customers with high monthly charges show higher attrition rates, indicating a sensitivity to price-to-value ratio.
* **Stickiness Factors:** Deeper service engagement—specifically **Online Security** and **Tech Support**—drastically reduces the likelihood of churn.
* **Billing Friction:** Users paying via **Electronic Check** have the highest churn rate compared to those on automated payment methods.

## High-Risk Customer Profile
Based on the analysis, the customers most likely to churn are those with:
1. Low Tenure (< 1 year)
2. Month-to-month contracts
3. High monthly charges
4. No additional security/support services

## Business Recommendations
* **Onboarding Focus:** Implement intensive retention efforts during the first 6 months.
* **Contract Incentives:** Offer small discounts to transition month-to-month users into 1-year or 2-year plans.
* **Value Bundling:** Bundle "Security" and "Tech Support" for high-value customers.
* **Payment Optimization:** Promote **Auto-pay** adoption to reduce billing-related friction.

## Repository Structure
```text
customer-churn-analysis/
│
├── data/               # Raw and processed datasets
├── notebooks/          # Jupyter notebooks with detailed EDA & Visualizations
├── images/             # Exported charts and dashboard screenshots
├── requirements.txt    # Requirements for the project to run locally  
└── README.md           # Project documentation
```
## How to Run
1. Clone the repository:
   ```text
   git clone https://github.com/your-username/Customer-Churn-Analysis.git
   ```
2. Install dependencies:
   ```text
   pip install -r requirements.txt
   ```
3. Launch the analysis:
   
    Explore the findings in
   ```text
   notebooks/Analysis.ipynb.
   ```
