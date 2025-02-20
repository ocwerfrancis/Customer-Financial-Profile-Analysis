# Customer Financial Profile Analysis

## Project Overview
This project aims to analyze customer credit card usage and financial health using two datasets:
1. **users_data.xlsx** – Contains demographic and financial details of users.
2. **cards_data.xlsx** – Contains details about each credit card linked to users.

### Objectives:
- Analyze customer demographics and financial profiles.
- Understand credit card ownership distribution.
- Assess credit risk based on user financial data.
- Identify expiring credit cards.
- Provide marketing insights for financial services.

## Dataset Description
### users_data.xlsx
This dataset includes:
- **User ID**: Unique identifier for each customer.
- **Age**: Age of the customer.
- **Income**: Customer’s annual income.
- **Employment Status**: Whether the user is employed, unemployed, or retired.
- **Credit Score**: A measure of financial health.
- **Other demographic details**.

### cards_data.xlsx
This dataset includes:
- **Card ID**: Unique identifier for each credit card.
- **User ID**: Links the card to a customer.
- **Card Type**: (e.g., Visa, MasterCard, etc.).
- **Credit Limit**: Maximum credit allowed on the card.
- **Expiration Date**: Card validity.
- **Outstanding Balance**: Remaining unpaid balance.

## Tools & Technologies Used
- **Python** (pandas, matplotlib, seaborn, numpy)
- **Jupyter Notebook**
- **SQL** (for data extraction and transformation)
- **Plotly** (for interactive visualizations)
- **Excel** (data storage and initial processing)

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone <repo-link>
   cd Customer-Financial-Profile-Analysis
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows use: env\Scripts\activate
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
5. Load and run Customer Financial Profile Analysis.ipynb.

## Key Insights & Expected Outcomes

- Identification of high-risk customers based on credit scores.

- Insights into credit card ownership trends by age, income, and employment.

- Prediction of potential defaults based on outstanding balances.

- Recommendations for targeted financial product offerings.

## Future Improvements

- Integration with real-time financial data.

- Machine learning models for predictive analytics.

- Web-based dashboard for interactive analysis.
