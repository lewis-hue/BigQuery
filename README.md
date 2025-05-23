
## Data Analysis in BigQuery

This project involves analyzing a B2B SaaS customer dataset with the aim of providing actionable insights related to customer retention, revenue growth, and strategic decision-making. The dataset includes critical variables such as monthly subscription, churn risk, NPS scores, support tickets, industry, and geographical data.

### Churn Risk and NPS Correlation
![Churn Risk and NPS Correlation](https://github.com/lewis-hue/BigQuery/blob/main/Churn%20Risk%20and%20NPS%20Correlation.png)

#### Analysis:
NPS (Net Promoter Score) serves as a key indicator of customer satisfaction and is highly correlated with churn risk.

Customers with Low Churn Risk have the highest average NPS score of 6.16, suggesting they are highly satisfied and more likely to stay with the company.

Customers with High Churn Risk have a significantly lower NPS score of 3.15, implying dissatisfaction and a higher likelihood of churn.

Customers in the Medium Churn Risk category have the lowest NPS score of 0.37, which indicates a critical group that is potentially on the edge of switching to competitors.

#### Business Implication:
Low churn risk customers are highly satisfied and should be retained with ongoing engagement and loyalty programs.

High churn risk customers should be targeted for intervention with personalized offers, improved customer support, or loyalty incentives to boost their satisfaction.

Medium churn risk customers require focused attention with tailored campaigns to increase satisfaction, particularly addressing their low NPS scores.


### Support Tickets Impact on Retention
![Support Tickets Impact on Retention](https://github.com/lewis-hue/BigQuery/blob/main/Support%20Tickets%20Impact%20on%20Retention.png)

#### Analysis:

The number of support tickets in the last 6 months appears to have a direct correlation with churn risk.

As the number of support tickets increases, the percentage of high churn risk customers also tends to rise, as observed in cases like support tickets = 22 (0.48 high churn risk) and support tickets = 19 (0.38 high churn risk).

There is also a noticeable dip in churn risk when support tickets are at 16 (0.06 high churn risk), showing that low support tickets correlate with low churn risk.

#### Business Implication:
High support ticket volume correlates with higher churn risk, suggesting that customer dissatisfaction is likely linked to increased support needs. This indicates that improving the customer service experience could lower churn.

Customers with higher support tickets should be targeted with proactive retention strategies, such as personalized follow-up, offering solutions to recurring issues, or improving the product/service based on frequent complaints.

### Revenue Contribution by Customer Segments (Industry-based)
![Revenue Contribution by Customer Segments](https://github.com/lewis-hue/BigQuery/blob/main/Revenue%20Contribution%20by%20Customer%20Segments%20(Industry-based).png)

#### Analysis:
The Technology and Healthcare industries generate the highest total revenue at $226,811.28 and $226,659.39, respectively.

Healthcare has the highest average revenue per customer at $2,575.67, indicating that it’s a high-value segment.

Finance and Manufacturing show lower ARPU figures, with Finance at $2,638.42 and Manufacturing at $2,568.51, suggesting that while their total revenue is still substantial, their profitability per customer is lower.

#### Business Implication:
Focus on Technology and Healthcare industries for high-value customer acquisition, as these industries bring in significant revenue and have strong customer spending patterns.

The Retail and Finance sectors may need additional marketing efforts or product offerings to boost their ARPU.

Industries with low ARPU could benefit from higher-margin products or services, improving profitability per customer.

### Predictive Churn Analysis by Support Tickets and NPS Score
![Predictive Churn Analysis by Support Tickets and NPS Score](https://github.com/lewis-hue/BigQuery/blob/main/Predictive%20Churn%20Analysis%20by%20Support%20Tickets%20and%20NPS%20Score.png)

#### Analysis:
Customers classified as Low Churn Risk represent 339 customers, contributing $873,568.29 in total revenue.

High Churn Risk customers are fewer in number (142 customers), but their revenue contribution ($341,785.77) is still substantial, suggesting that even high-risk customers bring in significant revenue.

The Medium Churn Risk group, though small in size (19 customers), generates a total revenue of $46,899.53.

#### Business Implication:
Low churn risk customers contribute the most revenue and should be nurtured with loyalty programs to prevent their potential transition to competitors.

High churn risk customers, despite contributing significant revenue, are at risk of leaving. Targeting them for special offers, customer service improvements, and personalized communication could help retain them.

The medium churn risk segment might require further analysis to understand why they are at risk and what could be done to reduce their churn probability while maintaining their revenue potential.


### Customer Segmentation by Monthly Subscription (Revenue)
![Customer Segmentation by Monthly Subscription](https://github.com/lewis-hue/BigQuery/blob/main/Customer%20Segmentation%20by%20Monthly%20Subscription%20(Revenue).png)

#### Analysis:

The Low ARPU segment, comprising 481 customers, generates the highest total revenue ($1,192,697.72), despite lower average revenue per user.

Medium and High ARPU segments generate significantly less total revenue, with Medium ARPU at $52,945.51 and High ARPU at $16,610.36, even though their individual subscription averages are higher.

#### Business Implication:
Low ARPU customers contribute the bulk of revenue, indicating that a large customer base with moderate subscriptions is still highly profitable. Focus should be on customer acquisition and retention in this segment.

The Medium and High ARPU segments, though smaller in customer count, contribute higher revenue per customer. These groups should be targeted with premium services or upselling strategies to increase their spending and overall contribution to revenue.




---

## ✅ Summary
Churn Risk & NPS: High NPS scores correlate with low churn risk, and addressing dissatisfaction (low NPS) should be a priority for retention.

Support Tickets: Higher support ticket volumes correlate with higher churn risk, indicating a need for proactive customer service improvements.

Revenue by Industry: Focus on high-value industries (Technology, Healthcare) for growth, while improving ARPU in sectors like Finance and Manufacturing.

Predictive Churn Analysis: High churn risk customers, despite their smaller numbers, bring significant revenue. Retention efforts are crucial.

Customer Segmentation: Low ARPU customers contribute the most revenue, while medium and high ARPU segments should be further optimized through premium services.

These analyses highlight areas where targeted retention, upselling, and industry-specific strategies can drive both short-term and long-term business growth.

### Looker Studio Data Visualization

### B2B SaaS Analysis Dashboard (Looker Studio)
![B2B SaaS Analysis Dashboard](https://github.com/lewis-hue/BigQuery/blob/main/B2B%20SaaS%20Dashboard.png)

- **B2B SaaS Analysis Dashboard (Looker Studio)**: [B2B SaaS Analysis Dashboard](https://lookerstudio.google.com/reporting/aa21172a-5a1f-4839-b179-01c32a73becf)
```{r}
