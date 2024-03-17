# Bank-Debts-Recovery
Exploratory Data anlaysis using Python and its framworks - Pandas, Numpy, Matplot

After a debt has been legally declared "uncollectable" by a bank, the account is considered to be "charged-off." But that doesn't mean the bank simply walks away from the debt. They still want to collect some of the money they are owed. The bank will score the account to assess the expected recovery amount, that is, the expected amount that the bank may be able to receive from the customer in the future (for a fixed time period such as one year). This amount is a function of the probability of the customer paying, the total debt, and other factors that impact the ability and willingness to pay.

The bank has implemented different recovery strategies at different thresholds ($1000, $2000, etc.) where the greater the expected recovery amount, the more effort the bank puts into contacting the customer. For low recovery amounts (Level 0), the bank just adds the customer's contact information to their automatic dialer and emailing system. For higher recovery strategies, the bank incurs more costs as they leverage human resources in more efforts to contact the customer and obtain payments. Each additional level of recovery strategy requires an additional $50 per customer so that customers in the Recovery Strategy Level 1 cost the company $50 more than those in Level 0. Customers in Level 2 cost $50 more than those in Level 1, etc.

The big question: does the extra amount that is recovered at the higher strategy level exceed the extra $50 in costs? In other words, was there a jump (also called a "discontinuity") of more than $50 in the amount recovered at the higher strategy level? We'll find out in this notebook.


**Project Overview**
This project focuses on analyzing bank debt recovery strategies using Python and its frameworks - Pandas, Numpy, and Matplotlib. The analysis aims to understand the effectiveness of different recovery strategies implemented by a bank once a debt is considered "charged-off."

**Objective**
The primary objective is to evaluate if the incremental costs invested in higher-level recovery strategies yield a corresponding increase in the amount recovered, ensuring the extra effort is financially justified.

**Dataset Introduction**
We start by loading a banking dataset that includes various details related to charged-off accounts and the recovery strategies employed. Initial data exploration involves understanding the dataset's structure, identifying missing values, and visualizing data distributions.

**Analysis Strategy**
  * Data Cleaning: Address missing values, outliers, and inconsistencies to ensure data quality.
  * Exploratory Data Analysis (EDA): Utilize statistical summaries and visualizations to understand the data's underlying patterns and trends.
  * Recovery Strategy Evaluation: Analyze the recovery amounts against the respective strategy levels and costs to identify the strategy effectiveness and any significant discontinuities in recovery amounts.
  * Modeling: Employ regression analysis or other relevant statistical methods to quantitatively assess the impact of recovery strategies on the recovered amount.
**Expected Outcomes**
  * The analysis should reveal whether higher recovery strategies (Level 1 and above), which are more resource-intensive, lead to a significant increase in recovery amounts that justify the additional $50 per customer expense. It aims to identify the optimal point where the recovery strategy becomes cost-effective.

**Visualizations**
* Include graphs such as the "Regression Discontinuity graph" to illustrate any significant jumps in recovery amounts that correlate with changes in recovery strategy levels.

<img width="533" alt="Screenshot 2024-03-17 at 6 00 50 AM" src="https://github.com/hritvikgupta/Bank-Debts-Recovery/assets/60143996/e6215b3d-e354-4710-9f81-73c3c112faaf">
<img width="928" alt="Screenshot 2024-03-17 at 6 01 17 AM" src="https://github.com/hritvikgupta/Bank-Debts-Recovery/assets/60143996/618cd5aa-adf9-43a3-9fa1-ea971b818a8b">



**Conclusion**
Summarize key findings regarding the efficiency of various debt recovery strategies, providing actionable insights for the bank to optimize its debt recovery efforts.

**How to Use**
Detail the steps to run the analysis, including the setup of the Python environment, necessary libraries, and execution of the notebook/script.

