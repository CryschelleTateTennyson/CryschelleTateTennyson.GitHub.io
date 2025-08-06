## Are Employees Meeting Their Quota?
<img src="images/THHS.png?raw=true"/>

---
It's fascinating how numbers can tell a story, and my recent project certainly proved this point. As I navigated through thousands of data points from Texas Health and Human Services, I realized that the stories behind the data were not just about compliance, but about the livelihoods and well-being of employees. 

---
### Why THIS Project?
When a new law mandated that Texas Health and Human Services employees maintain a 95% productivity rate during their work hours, it became clear that measuring and understanding employee performance was essential. With potential job losses looming over the staff, supervisors tasked me with providing a way to track employee productivity effectively.

---
### What Readers Will Gain
In this article, I will take you through my analysis process, share key findings about employee productivity, and discuss what these results mean for the workforce. You will also see how simple data visualization can reveal crucial insights for any organization.

---
### Key Takeaways
•	Many employees at Texas Health and Human Services are falling short of their required work hours.
•	Even with overtime, a large number of employees still do not meet the quota.
•	While break times are within acceptable limits, significant idle time (GAP) is impacting productivity.

---
### Dataset Details
The dataset I worked with was provided directly by Texas Health and Human Services and comprised a whopping 31,995 rows, tracking employee information across 11 columns. Alongside structured data, there was unstructured information from time sheets detailing daily activities. This rich data was a treasure trove for identifying productivity patterns.

---
### Analysis Process
I began by talking with the supervisors at Texas Health and Human Services to make sure I understood what they were asking of me and to verify my understanding of the data. I then began cleaning and organizing the data to get a clearer picture of employee hours worked. I calculated the GAP time by factoring in breaks and lunch. This led to a compelling analysis of whether employees were meeting their productivity quotas. The surprising outcome was the realization that even with additional hours worked, many employees were still not able to reach the expected benchmarks.

---
### Visuals and Insights
I created a time entry slot that allows supervisors to enter employee time and Excel to spit out a dashboard detailing the employees’ timed worked.

<img src="images/THHS1.jpg?raw=true"/>
<img src="images/THHS2.jpg?raw=true"/>

Employee time from 7/20/2025 – 7/26/2025 was entered into the log above, the results can be found in the Excel dashboard below.

<img src="images/THHS3.jpg?raw=true"/>

I included several visuals to represent the data effectively:

•	**Conversion:**
I started with a conversion chart that shows how many hours, and its equivalent percentage, should be worked each day to meet the 95% quota at the end of the week. 

<img src="images/THHS4.jpg?raw=true"/>

The days are numbered so that if an employee misses a day or there is a holiday, supervisors can simply look at the number of days worked and determine how much time they should have worked.

•	**Daily Work Hours vs. Required Hours:**  
This chart clearly shows how many hours each employee worked compared to the required amount. The black bars represent the daily quota. 

  	<img src="images/THHS5.jpg?raw=true"/>

What stood out in this chart was the stark number of employees whose bars are under the 5th black line, indicating that they did not meet their 5-day quota.

•	**Overtime Analysis:**  
The second chart illustrates total hours worked, including overtime. The employees failing to meet the quota are highlighted in red. 

   	<img src="images/THHS6.jpg?raw=true"/>

This visual surprised me because it highlighted that even with overtime, the quota was still unattainable for many, raising questions about workload management.

•	**Gap Time Analysis:**  
Contrary to initial concerns about excessive break times, which should be seven and a half hours a week or less, my analysis showed that employees had considerable GAP time instead. 

  	 <img src="images/THHS7.jpg?raw=true"/>
     <img src="images/THHS7.jpg?raw=true"/>

This insight shifts the focus from break management to addressing the idle time that could be better utilized.

---
### Main Takeaways
•	The analysis indicated a significant gap in productivity with many employees still unable to meet their quotas, even when working overtime.
•	Break times were not excessively long; the main issue was idle time throughout the workday, calling for a need for better time management and efficiency strategies.
•	Supervisors could benefit from tailored interventions focused on reducing GAP time, ultimately leading to improved compliance with the new law.

---
### Conclusion and Personal Reflections
This project taught me a great deal about not just data analysis, but the real-life implications that data can have on people's jobs and livelihoods. One challenge I faced was implementing a dashboard that is connected to a log that will be continuously updated by supervisors. I was not used to creating something for others to use that would have continuous inputs, but I learned to do just that. The experience underscored the importance of clear communication with stakeholders when beginning a project and of findings when presenting a project, especially when it involves people's careers.

For organizations facing similar challenges, I recommend implementing regular assessments of employee productivity while providing support for time management. By focusing on reducing GAP time, companies can help their employees meet their work quotas and maintain job security.

---
### Call to Action
I’d love to hear your thoughts on my findings! Connect with me on LinkedIn, or if you know someone looking to hire a data analyst, let’s have a conversation. Leave a comment with your insights or questions!

