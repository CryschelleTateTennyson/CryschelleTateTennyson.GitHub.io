# Are Hospitals Following Best Practices?
<img src="images/hospital.png?raw=true"/>

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
The dataset I worked with was quite extensive, provided by the president of Mega Corporation. It comprises two tables: health and demographics, covering data on 101,000 patients. The size and diversity of this dataset made it suitable for answering the pressing questions posed by the hospital manager.

---
#### Analysis Process
My analysis journey started with cleaning the data to ensure it was accurate and usable. For instance, I noticed that some columns had incorrect data types, which I corrected. For example, I changed the "time_in_hospital" variable from a string to an integer, allowing for proper calculations.
<img src="images/h1.jpg?raw=true"/>
H2
I then summarized the data to get a clearer picture of patients and their hospital experiences. Summary information from the health table:
H3
Summary information from the demographics table:
H4
After that, I created a histogram to understand patient stay durations better.
H5

---
#### Insights
ARE PROCEDURES BEING DONE FAIRLY?
-	Analyzing the distribution of procedures by medical specialty showed that surgery-related specialties were performing the most procedures. This made me think about how surgery often carries a higher risk than other procedures.
H6
-	When examining the demographics, I found that the number of lab procedures performed was fairly consistent across races, averaging between 40 and 44. This suggests that MegaHospital is treating patients equitably. 
H7
-	Looking at the correlation between the hospital stay lengths and the number of procedures, I observed that more procedures typically led to longer stays. ‘Few procedures’ averaged 3.8 days, while ‘many procedures’ averaged 5.66 days, indicating a logical pattern in patient care.
H8
WHICH MEDICATIONS ARE BEING USED THE MOST?
-	Next, I analyzed medication usage. Insulin stood out as the most prescribed medication across all age groups. It was surprising to see that Metformin and Glipizide swapped places for those 80 and older, highlighting how treatment can evolve with age.
H9
-	The hospital manager also asked for a written report on the top 50 medication patients.
H10
WHAT ARE THE BIGGEST SUCCESS STORIES?
-	Lastly, I uncovered a significant number of success stories, with over 33,000 patients leaving the hospital sooner than average after emergencies. This was a heartwarming finding, emphasizing the positive impact the hospital has on patient recovery.
H11

---
#### Main Takeaways
1. **Fairness in procedures**: The data showed that regardless of race, patients received similar care in terms of lab procedures performed.
2. **Medication patterns**: Insulin's prevalence across age groups indicates a strong focus on managing diabetes in the hospital's patient population.
3. **High success rates**: The sheer number of success stories demonstrates the effectiveness of the hospital’s emergency response and treatment protocols.

---
#### Conclusion and Personal Reflections
This project taught me a lot about the intricacies of hospital operations and the importance of data integrity. I faced challenges, like data cleaning and ensuring accurate interpretations, but overcoming them brought a sense of accomplishment. I look forward to the fifth project of my challenge.

I’d love to hear your thoughts on my findings! Connect with me on LinkedIn, or if you know someone looking to hire a data analyst, let’s have a conversation. Leave a comment with your insights or questions!
