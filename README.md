# RFM-ANALYSIS-PROJECT

RFM Analysis Overview:
This repository encompasses a detailed RFM (Recency, Frequency, Monetary) analysis performed on a dataset, offering insights into customer behavior and engagement. RFM analysis is a powerful method used in marketing to segment and target customers based on their transaction patterns.

Dataset:
The dataset used for this analysis contains transactional data, including customer IDs,Monetory,Units, purchase dates. It serves as the foundation for deriving valuable insights through RFM metrics.

RFM Metrics:
Recency (R):
Reflects how recently a customer made a purchase.
Calculated as the difference between the last purchase date and the present date.
Frequency (F):
Represents how often a customer makes a purchase.
Determined by the total number of transactions made by the customer.
Monetary (M):
Indicates the total monetary value of a customer's transactions.
Obtained by summing up the monetary values of all transactions made by the customer.
Analysis Insights:
The analysis provides insights into customer segments based on their RFM scores. These segments can be utilized for targeted marketing strategies, personalized communication, and optimizing customer engagement.

Excel Formulas Used:
To perform the RFM analysis, the following Excel formulas were employed:

Recency (R):
=TODAY() - Last_Purchase_Date

Frequency (F):
=COUNTIF(New_id, New_id)

Monetary (M):
=SUMIF(New_id,New_id ,Monetory)

= Persentile(Max,0.33)
=CONCAT(Recency_score,Frequency_score,Monetory_score)

Utilize the provided Excel formulas to calculate Recency, Frequency, and Monetary values.

RFM Analysis:
Leverage the RFM scores to segment customers and tailor marketing strategies accordingly.
Project Presentation:
Title:
RFM Analysis: Understanding Customer Segmentation

Author:
Pankaj Rana

Project Description:
This project focuses on RFM analysis, a data-driven approach to understanding and segmenting customers based on their recency, frequency, and monetary metrics. The provided Excel formulas facilitate easy implementation of the RFM framework on your own transactional dataset.
