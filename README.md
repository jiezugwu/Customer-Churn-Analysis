Customer Churn Projects

DESCRIPTION:
This project investigates whether the customer information already stored by the business—age, gender, income, spending score, membership length, online purchases, and discount use—can reliably predict which customers are likely to churn. It performs a full end‑to‑end analysis:

Validates the dataset (2,000 customers; no missing values; clean churn labels).
“Complete: no missing values and no duplicate customers.”

Compares churn across 31 predefined customer groups (age bands, tenure bands, quartiles of income, spending, purchases, discount use, and gender).

Tests each customer detail individually to see whether leavers differ from stayers in any meaningful way.
“In every case the difference is small and fully consistent with chance.”

Builds and evaluates a logistic‑regression churn model, using strict pre‑defined standards (AUC > 0.55; top‑10% lift > 1.24).
“A prediction model that used all seven details together did no better than guessing. Its score was 0.496.”

Benchmarks the model against pure noise by scrambling churn labels 30 times.

Produces a stakeholder dashboard summarizing churn rates, uncertainty ranges, and model performance.

The project ultimately answers one decision question: Should the retention team use these customer details to target retention offers?

Why the project is useful?
This project is valuable because it prevents the business from making costly, misleading, or biased decisions based on weak data:

It avoids wasted investment.  
The analysis shows that none of the seven customer details meaningfully predict churn.
“None showed a clear link to leaving. Customers who left looked much like customers who stayed.”   
Without this project, the business might have built a churn model that performs no better than chance.

It protects against false patterns.  
With 31 customer groups, random variation can make some groups appear “high risk.”
“With 31 groups, one of them is always going to be the tallest, even when nothing is going on.”   
The project prevents stakeholders from acting on flukes.

It reframes the strategy toward evidence‑based action.  
Since customer details cannot identify who is at risk, the project recommends a randomized retention‑offer pilot—the only reliable way to measure whether an offer actually reduces churn.

It highlights missing data needed for future predictive work.  
“Collect richer information (for example, date of last purchase and number of support tickets) before trying to predict churn again.”   
This guides future data collection and analytics investment.

It improves decision quality and fairness. 

The project prevents targeting based on age or gender—attributes that show no signal and could raise ethical or legal concerns.

The kaggle link to the dataset: https://www.kaggle.com/datasets/ihasan88/customer-behavior-and-churn-prediction-dataset

Also for more information: You can check out the case study 
