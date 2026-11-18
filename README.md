# RFM-Analysis-for-Retail-Data
RFM-based customer segmentation in Python that scores customers on Recency, Frequency and Monetary value, groups them into segments like Champions, Loyal and At Risk, and analyzes spending by age and marital status.

## What it does

- **Data prep:** Loads customer master and transaction data, converts date fields to datetime, and drops transactions that have no matching customer record.

- **RFM metrics:** Calculates Recency (days since the last purchase, counted from one day after the latest transaction), Frequency (number of transactions) and Monetary (total spend) for each customer.

- **Scoring:** Scores each metric from 1 to 5 using fixed thresholds and combines the three into a single RFM score (e.g. `545`).

- **Segmentation:** Uses rules to sort customers into Champions, Loyal Customers, Potential Loyalist, At Risk, Lost, Big Spenders and Others.

- **Demographic insights:**

  - Age bracket mix within each segment (counts and % share)

  - Total, average and median spend by age bracket

  - Spending patterns by marital status
 
  - RFM_Analysis.ipynb

IPYNB

Based on this code, understand the context, and based on that write a crisp, to the point description for Github upload.

 

Repo “About” line (fits GitHub’s 350-character limit):

Customer segmentation using RFM (Recency, Frequency, Monetary) analysis in Python. It scores customers on a 1 to 5 scale, sorts them into segments such as Champions, Loyal and At Risk, and compares spending by age group and marital status.

README description:

 

markdown

# Customer Segmentation using RFM Analysis

 

Segments customers by purchase behaviour using RFM (Recency, Frequency, Monetary) analysis, then profiles each segment by age and marital status.

 

## What it does

- **Data prep:** Loads customer master and transaction data, converts date fields to datetime, and drops transactions that have no matching customer record.

- **RFM metrics:** Calculates Recency (days since the last purchase, counted from one day after the latest transaction), Frequency (number of transactions) and Monetary (total spend) for each customer.

- **Scoring:** Scores each metric from 1 to 5 using fixed thresholds and combines the three into a single RFM score (e.g. `545`).

- **Segmentation:** Uses rules to sort customers into Champions, Loyal Customers, Potential Loyalist, At Risk, Lost, Big Spenders and Others.

- **Demographic insights:**

  - Age bracket mix within each segment (counts and % share)

  - Total, average and median spend by age bracket

  - Spending patterns by marital status
