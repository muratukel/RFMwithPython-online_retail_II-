## RFM Analysis: Understanding Customer Segmentation 🕐📟💲

![img](https://analyticahouse.com/Website/assets/img/Blogs/6314b7a379496.png)

RFM (Recency, Frequency, Monetary) analysis is a method used for customer segmentation and crafting marketing strategies. RFM stands for the initials of its three core components. This analysis aims to categorize customers based on specific criteria and divide them into different segments.

✔️Key Concepts of RFM Analysis:

🔸Recency (R):

Represents the time that has passed since a customer's last purchase.Customers with more recent purchases are generally considered more valuable, as they are likely to engage in repeated transactions.

🔸Frequency (F):

Indicates how often a customer makes purchases within a specific time frame.Customers who shop frequently are often considered more loyal and valuable.

🔸Monetary (M):

Refers to the total amount of money a customer has spent.Customers who have made significant purchases are often more financially impactful and potentially more
responsive to special offers.

✔️RFM Segmentation Categories:

🔸Champions:

Customers with high recency, frequency, and monetary values.

🔸Valued Customers:

Customers with highmonetary value but potentially lower recency and frequency.

🔸Recoverable Customers:

Customers with low recency, moderate frequency, and monetary values.This segment includes customers who can be re-engaged.

🔸At Risk Customers:

Customers with low recency, low frequency, and monetary values.These customers are at risk of attrition.

🔸Lost Customers:

Customers with the lowest recency, frequency, and monetary values.This segment generally includes customers who are harder to re-engage.

RFM analysis is used to personalize marketing strategies, enhance customer loyalty, and create targeted campaigns for specific segments. It provides insights into customer behaviors and enhances the effectiveness of marketing efforts.

## Dataset Link : https://archive.ics.uci.edu/dataset/502/online+retail+ii


## 💱Let's randomly choose three segments and interpret them.

| Segment              | Recency (mean) | Recency (median) | Recency (count) | Recency (std) | Frequency (mean) | Frequency (median) | Frequency (count) | Frequency (std) | Monetary (mean) | Monetary (median) | Monetary (count) | Monetary (std) |
|----------------------|----------------|------------------|-----------------|---------------|-----------------|-------------------|------------------|----------------|-----------------|-------------------|-----------------|---------------|
| About to Sleep       | 52.85          | 52.0             | 343             | 10.26         | 1.20            | 1.0               | 343              | 0.40           | 442.27          | 317.76            | 343             | 417.30        |
| At Risk              | 150.93         | 129.0            | 611             | 69.98         | 3.07            | 3.0               | 611              | 1.09           | 1188.21         | 760.19            | 611             | 1844.17       |
| Can't Loose          | 122.72         | 107.5            | 78              | 49.72         | 9.04            | 7.5               | 78               | 5.78           | 4072.97         | 2316.48            | 78              | 5275.40       |
| Champions            | 6.12           | 6.0              | 663             | 4.62          | 12.50           | 8.0               | 663              | 17.19          | 6852.26         | 2508.32            | 663             | 21556.38      |
| Hibernating          | 213.31         | 212.0            | 1016            | 89.78         | 1.13            | 1.0               | 1016             | 0.33           | 401.98          | 250.16             | 1016            | 775.08        |
| Loyal Customers      | 35.28          | 30.0             | 743             | 16.06         | 6.82            | 5.0               | 743              | 4.38           | 2743.48         | 1818.71            | 743             | 3255.11       |
| Need Attention       | 52.21          | 52.0             | 207             | 9.83          | 2.45            | 2.0               | 207              | 0.50           | 1058.79         | 730.47             | 207             | 1190.26       |
| New Customers        | 7.58           | 7.5              | 50              | 4.31          | 1.00            | 1.0               | 50               | 0.00           | 386.20          | 258.83             | 50              | 493.32        |
| Potential Loyalists  | 17.77          | 18.0             | 516             | 9.73          | 2.02            | 2.0               | 516              | 0.70           | 729.16          | 523.66             | 516             | 837.55        |
| Promising            | 24.76          | 24.0             | 87              | 6.03          | 1.00            | 1.0               | 87               | 0.00           | 368.02          | 293.74             | 87              | 343.91        |


## 📝Loyal Customers

🖇️There are 743 individuals in this segment.

🖇️They have an average recency of 35.28 days without making a purchase.

🖇️They have made an average of 6.8 transactions.

🖇️They have generated an average monetary value of 2743.48.

## 📝Based on this information, a possible action decision could be:

Considering that these customers have a relatively high frequency of purchases and have generated a substantial monetary value, the focus could be on maintaining their engagement and encouraging more frequent purchases. Sending personalized offers, loyalty rewards, and exclusive deals could incentivize them to continue their shopping habits. Additionally, gathering feedback from these customers to understand their preferences better and tailoring marketing strategies accordingly could help solidify their loyalty.

## 📝Promising

🖇️There are 87 individuals in this segment.

🖇️They have an average recency of 24.76 days without making a purchase.

🖇️They have made an average of 1 transactions.

🖇️They have generated an average monetary value of 368.02

## 📝Considering the characteristics of this segment, a potential action decision could be:

Given that these customers have relatively infrequent transactions and a low average monetary value, the focus could be on converting them into more active and engaged customers. To do so, tailored marketing campaigns could be employed to showcase the value and benefits of additional purchases. Special promotions, discounts, or targeted product recommendations based on their past behavior could be used to encourage them to increase their transaction frequency and monetary contributions. Regular follow-ups and personalized communication might also help nurture their interest and establish a stronger connection with your brand.

## 📝About to Sleep

🖇️"About to Sleep" segment consists of 343 individuals.

🖇️On average, customers in this segment have not made a purchase for around 52.85 days, with a median of 52 days.

🖇️The standard deviation is relatively low at 10.26, indicating consistency in this aspect.

🖇️The average frequency of transactions is 1.20, with a median of 1. This suggests that most customers in this segment have made very few purchases.

🖇️In terms of monetary value, the average is 442.27, and the median is 317.76. The standard deviation of 417.30 indicates some variability in the spending patterns.

## 📝Based on these insights, a potential interpretation and action plan could be:

The "About to Sleep" segment represents customers whose engagement with your business is declining. While they may have made very few transactions, the frequency of repeat transactions and their monetary value are not promising. To address this situation, we should consider re-engagement strategies. Targeted offers, personalized recommendations or sending messages that remind them of their past positive experiences can reignite their interest. We need to analyze their purchase history to identify their preferences and adapt communications accordingly. The goal is to potentially convert them from inactive customers to more frequent buyers, which will help improve their repeat frequency and monetary value.
