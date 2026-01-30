## Understanding Loany's Loan Dynamics
<img src="images/Loany.png?raw=true"/>

---
I recently completed an analytics project designed to mirror the responsibilities of a financial analytics role I was applying for. Rather than simply listing technical skills, I wanted to demonstrate how I approach real business problems—by turning job requirements into a working data model and actionable insights.

---
### Why I Chose This Project
In a competitive job market, I wanted to show more than proficiency with SQL or financial concepts. I created a fictional loan company, Loany, and built a dataset to replicate a loan servicing environment, including client portfolios, loan balances, cash flow projections, and customer correspondence. This project became an opportunity to connect technical analysis with business decision-making.

---
### What You Will Learn
In this article, I walk through Loany’s insights uncovered from the analysis, including:
- Portfolio composition by client
- Expected cash flow and revenue drivers
- The effectiveness of client communication strategies
  
Whether you are interested in financial analysis, data analysis, or loan portfolio management, this project highlights how data can support operational and strategic decisions.

---
### Key Takeaways
-	**Immunity Lending** carries the highest total loan balance despite having the fewest active loans, suggesting a concentration in higher-balance products such as mortgages.
  
-	**February** shows the strongest projected cash flow, with **Island Bank’s portfolio** contributing the largest share of expected revenue.
  
-	The **High Balance Outreach** campaign and **in-house vendors** demonstrate strong early performance, with high response and delivery rates that warrant further evaluation for payment conversion.

---
### Delving into the Dataset
This analysis was powered by a SQL-based dataset I designed, consisting of six interconnected tables covering clients, loans, payment projections, and letter communications. Building the dataset allowed me to validate assumptions, troubleshoot data integrity issues, and tailor the structure to real-world analytical needs.

<img src="images/l1.jpg?raw=true"/>
<img src="images/loany1.2.png?raw=true"/>

---
### My Analysis Journey
I began by validating the integrity of the dataset to ensure all downstream analysis would be reliable. This included confirming that no loan payments exceeded their principal balances and verifying that all loans were associated with existing clients. The absence of results in these validation queries confirmed that the data was consistent and suitable for analysis.

*Input:*
img src="images/loany2.png?raw=true"/>
*Output:*
<img src="images/l1.jpg?raw=true"/>

*Input:*
img src="images/loany3.png?raw=true"/>
*Output:*
<img src="images/l1.jpg?raw=true"/>

Next, I analyzed portfolio composition by client to understand overall exposure and activity levels. While **Immunity Lending** had the fewest active loans, it carried the highest total outstanding balance, suggesting a concentration in higher-balance loans such as mortgages rather than consumer products.

*Input:*
img src="images/loany4.png?raw=true"/>
*Output:*
<img src="images/l1.jpg?raw=true"/>

I then shifted focus to **cash flow forecasting**, aggregating expected payments weighted by probability. This analysis showed that **February** represents the strongest projected collection month, with **Island Bank’s portfolio** contributing the largest share of expected cash flow. This highlights a potential opportunity to prioritize operational focus on these accounts.

*Input:*
img src="images/loany5.png?raw=true"/>
*Output:*
<img src="images/l1.jpg?raw=true"/>
<img src="images/l1.jpg?raw=true"/>

*Input:*
img src="images/loany6.png?raw=true"/>
*Output:*
<img src="images/l1.jpg?raw=true"/>
<img src="images/l1.jpg?raw=true"/>

Breaking projections down by loan type confirmed that **mortgage loans significantly outperform consumer loans** in expected revenue, driven by higher balances and stronger payment probabilities.

*Input:*
img src="images/loany7.png?raw=true"/>
*Output:*
<img src="images/l1.jpg?raw=true"/>
<img src="images/l1.jpg?raw=true"/>

Finally, I evaluated **letter effectiveness and operational performance**. The *High Balance Outreach* campaign achieved a **100% response rate**, and letters sent through *in-house vendors* demonstrated a **100% delivery rate**. While response rates alone do not guarantee revenue, these results indicate promising areas for deeper analysis, particularly around payment conversion following responses.

*Input:*
img src="images/loany8.png?raw=true"/>
*Output:*
<img src="images/l1.jpg?raw=true"/>

*Input:*
img src="images/loany9.png?raw=true"/>
*Output:*
<img src="images/l1.jpg?raw=true"/>

---
### Key Takeaways and Reflections
This project emphasized the importance of **storytelling through data**, not just technical querying. Designing the dataset and validating assumptions mirrored real-world analytical workflows. One notable insight was how **Immunity Lending’s high total balance**, despite fewer loans, may signal an opportunity to tailor mortgage-focused strategies for similar clients.

---
### Recommendation
Based on these findings, Loany should further evaluate the High Balance Outreach campaign using in-house vendors, focusing on **payment conversion rates and long-term revenue impact**. Expanding this approach to other high-balance segments could improve overall collections and forecasting accuracy.

---
### Let's Connect
This project reinforced my interest in applying financial analysis to real operational challenges. I would love to hear your feedback or discuss the approach in more detail. Feel free to connect with me on LinkedIn—especially if you or someone you know is looking for a financial analyst who enjoys turning data into insight.
