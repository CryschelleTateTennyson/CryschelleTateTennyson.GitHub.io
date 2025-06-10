# Are Hospitals Following Best Practices?
<img src="images/Hospital.png?raw=true"/>

---
When I first received the dataset from MegaHospital, I was intrigued by the challenge ahead. Hospitals play a crucial role in our lives, and I wanted to see if the practices at MegaHospital were truly serving their patients well. This is my fourth project in my challenge by the president of the Mega Corporation to analyze eight of its companies. My task for this company was to provide insights for the hospital manager.

---
#### Why THIS Project?
Accepting this project was an easy decision for me. Hospitals are often the frontline of healthcare, and understanding how they operate can lead to better patient experiences. The manager of the hospital wanted the answers to three main questions: Are procedures being done fairly? Which medications are the most commonly used? And what are the biggest success stories? These inquiries resonate with anyone who has ever been a patient or has a loved one in care.

---
#### What Readers Will Gain
In this article, you’ll learn about the insights I found regarding hospital practices at MegaHospital. I’ll share key findings about medication usage, procedure fairness, and patient success stories that might surprise you. 

---
#### Key Takeaways
- Procedures at MegaHospital are being performed fairly across different demographics.
- Insulin is the most commonly prescribed medication for every age group.
- There are more than 33,000 documented success stories.

---
#### Dataset Details
The dataset I worked with was quite extensive and comprises two tables: health and demographics, covering data on 101,000 patients. The size and diversity of this dataset made it suitable for answering the pressing questions posed by the hospital manager.

---
#### Analysis Process
- My analysis journey started with cleaning the data to ensure it was accurate and usable. For instance, I noticed that some columns had incorrect data types, which I corrected. For example, I changed the "time_in_hospital" variable from a string to an integer, allowing for proper calculations.
<img src="images/H1.jpg?raw=true"/>
<img src="images/H2.jpg?raw=true"/>
- I then summarized the data to get a clearer picture of patients and their hospital experiences. Summary information from the health table shows that the table has 101,766 patients, 73 medical specialties, 136,339 procedures, 4,385,671 lab procedures, and 1,630,479 medications:
<img src="images/H3.jpg?raw=true"/>
- Summary information from the demographics table shows that the table has 71,518 patinets, 6 races, and 10 age groups:
<img src="images/H4.jpg?raw=true"/>
- After that, I created a histogram to understand patient stay durations better.
<img src="images/H5.jpg?raw=true"/>

---
#### Insights
*Are procedures being done fairly?*
-	Analyzing the distribution of procedures by medical specialty showed that surgery-related specialties were performing the most procedures. This made me think about how surgery often carries a higher risk than other procedures.
<img src="images/H6.jpg?raw=true"/>
-	When examining the demographics, I found that the number of lab procedures performed was fairly consistent across races, averaging between 40 and 44. This suggests that MegaHospital is treating patients equitably. 
<img src="images/H7.jpg?raw=true"/>
-	Looking at the correlation between the hospital stay lengths and the number of procedures, I observed that more procedures typically led to longer stays. ‘Few procedures’ averaged 3.8 days, while ‘many procedures’ averaged 5.66 days, indicating a logical pattern in patient care.
<img src="images/H8.jpg?raw=true"/>

*Which medications are the most commonly used?*
-	Next, I analyzed medication usage. Insulin stood out as the most prescribed medication across all age groups. It was surprising to see that Metformin and Glipizide swapped places for those 80 and older, highlighting how treatment can evolve with age.
<img src="images/H9.jpg?raw=true"/>
-	The hospital manager also asked for a written report on the top 50 medication patients.
<img src="images/H12.jpg?raw=true"/>

*What are the biggest success stories?*
-	Lastly, I uncovered a significant number of success stories, with over 33,000 patients leaving the hospital sooner than average after emergencies. This was a heartwarming finding, emphasizing the positive impact the hospital has on patient recovery.
<img src="images/H13.jpg?raw=true"/>

---
#### Main Takeaways
1. **Fairness in procedures**: The data showed that regardless of race, patients received similar care in terms of lab procedures performed.
2. **Medication patterns**: Insulin's prevalence across age groups indicates a strong focus on managing diabetes in the hospital's patient population.
3. **High success rates**: The sheer number of success stories demonstrates the effectiveness of the hospital’s emergency response and treatment protocols.

---
#### Conclusion and Personal Reflections
This project taught me a lot about the intricacies of hospital operations and the importance of data integrity. I faced challenges, like data cleaning and ensuring accurate interpretations, but overcoming them brought a sense of accomplishment. I look forward to the fifth project of my challenge.

I’d love to hear your thoughts on my findings! Connect with me on LinkedIn, or if you know someone looking to hire a data analyst, let’s have a conversation. Leave a comment with your insights or questions!
