## Understanding Why Employee Attrition Is Rising
<img src="images/HR.png?raw=true"/>

---
In my journey as a data analyst, I’ve had the chance to tackle various interesting projects. However, one of the most thought-provoking assignments was with Mega IMB, where I explored the reasons behind increasing employee attrition. It was a real eye-opener, not just for me, but potentially for the company as well.

---
### Why THIS Project?

When I received the call from the president of Mega Corporation informing me that for my seventh project in my challenge, I would be working with Mega IMB, I was not expecting to dive into a topic as critical as employee attrition. The Human Resources manager of Mega IBM explained the rising trend of people leaving the company, and I knew this was not just about numbers; it was about people and their experiences at work. This project resonated with me because I believe that understanding the workplace dynamics can lead to better environments for everyone involved.

---
### What Readers Will Gain

By reading this article, you’ll learn about the factors influencing employee retention, particularly focusing on age and income. You'll also see how data can provide insights that help in making informed decisions in a corporate setting.

---
### Key Takeaways

- Older employees typically earn more and have longer tenure.
- Younger employees show a greater tendency to leave the company.
- Age and total working years account for almost 60% of income variation.

---
### Dataset Details

The dataset for this project came from the HR manager at Mega IMB. It contains 1,470 records of employees, with multiple columns detailing their demographics and job-related information. This rich dataset was crucial because it allowed for a deep dive into various employee characteristics that could impact attrition.

---
### Analysis Process

I started by cleaning the dataset to ensure the data was accurate for analysis and reading the dataset into R. (Image 1)

---
#### Visuals and Insights
Which Demographics Have the Strongest Relationships?
-	My first step was to look for correlations between different demographics. The correlation matrix I created shows that the strongest relationships are between 'Age' and 'Total Working Years' (0.680) and 'Monthly Income' and 'Total Working Years' (0.773). (Image 2)
-	When visualizing these correlations, it became clear that older employees not only had more experience but also higher incomes. (Image 3)

Is Attrition Influenced by Younger Age?
-	To investigate if younger employees were leaving at a higher rate, I created a boxplot comparing the ages of employees who stayed versus those who left. The data indicated that employees who departed were younger. (Image 4)
-	The results from a hypothesis test (p-value: 1.38e-08, average age of employees that stayed: 38, average age of employees that left: 34) confirmed this finding, illustrating that younger employees were indeed at a greater risk of leaving. (Image 5)

Can a linear regression model predict monthly income based on age?
-	I also created a linear regression model to see how well age could predict monthly income. The initial model revealed that only 24.79% of income variation could be explained by age alone. (Image 6)
-	When I included total working years in the model, the explanation improved significantly, accounting for 59.88% of income variation. This indicates that a combination of age and experience plays a vital role in determining income. In the future, this will allow Mega IBM to see if income is also tied to attrition. (Image 7)

---
### Main Takeaways

- The analysis confirmed that older employees generally earn more due to their longer tenure.
- The difference in age between employees who left and those who stayed highlights the need for companies to understand the younger workforce's motivations.
- Predicting income accurately requires considering multiple factors, as seen from the improved model when adding working years.

---
### Conclusion and Personal Reflections

Working on this project taught me a lot about how data can shine a light on real issues within a company. I faced challenges during the analysis, especially in cleaning the data and ensuring its accuracy. However, overcoming these hurdles made the findings even more rewarding.

This experience has reshaped my understanding of workforce dynamics. I believe that by addressing these insights, companies can create better retention strategies and improve workplace cultures. I am looking forward to my final project in my challenge by the president.

I’d love to hear your thoughts on my findings! Connect with me on LinkedIn, or if you know someone looking to hire a data analyst, let’s have a conversation. Leave a comment with your insights or questions!

