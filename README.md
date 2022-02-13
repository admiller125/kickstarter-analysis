# Kickstarting with Excel

## Overview of Project
	This project utilized basic excel functions to organize data relating to Kickstarter campaigns. Data was manipulated to provide columns of additional information allowing for further modularity using filters. The data was then used to create pivot tables and charts to allow the data to be more easily analyzed.

### Purpose
Through manipulating and organizing the data, visualizations were created that allowed us to make determinations regarding when to launch a Kickstarter and how much should be requested as a goal in the hopes of meeting fundraising requirements.


## Analysis and Challenges
	In order to expand on the data analysis of the module an additional column was created called "Years" and additional functions were used for simple mathematical analysis such as the sum() and countifs() functions.

### Analysis of Outcomes Based on Launch Date
In the "Outcomes Based on Launch Date" analysis, the data of the outcomes (successful, failed, or canceled) was compared to the months of the year. Filters of "Parent Category" and "Years" were created in order to further drill down into the data. The "Parent Category" was changed to "theater" to help provide context to which month the most successful theater Kickstarters. A pivot chart was then created to help visualize the data.  

### Analysis of Outcomes Based on Goals
In the "Outcomes Based on Goals" analysis, the data of the projects success and failure was calculated using the countifs() function. The total projects were then summed up and the success and failure percentages were calculated. This was then displayed on a line chart. 

### Challenges and Difficulties Encountered
The analysis in this exercise was straightforward, however I did run into a minor roadblock. Superfluous information in the form of "live" Kickstarters provided irrelevant detail and reduced the clarity of the analysis. As a result this was remedied by deleting the data and redoing the data organization for the "Outcomes by Launch Date" portion of the analysis.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	A couple of takeaways can be drawn from the data collected. The "Outcomes based on Launch Date" deliverable, displayed that Kickstarters that occur during the middle of the year have the highest success rate whereas the end of the year has the lowest success rate. It seems that there is sufficient evidence that there is at least some seasonality to people's likelihood of contributing to Kickstarter campaigns. 

- What can you conclude about the Outcomes based on Goals?
The "Outcome Based On Goals" deliverable displayed that once a smaller Kickstarter asks for above $15000 the probability of failure becomes more likely than success. The probability of success increases again between $35000 to $44999. This information however can be misleading due to the lack of data on who is trying to raise money.  

- What are some limitations of this dataset?
Information on individual or institutions that are trying to raise money on Kickstarter would be useful in determining how much money to request as a goal. One example is a YouTube personality running a business requesting funding for a theater production might have no issue raising between $35000 to $44999, but this would have little relevance to Louise unless she is in a similar situation. Additional information regarding whether an institution or an individual (designation of institution would be defined as an entity that pays more than one employees) would be useful. Another piece of data that would be particularly useful might be social media presence as quantified by number of followers across platforms or amount of engagement.


- What are some other possible tables and/or graphs that we could create?
Although certain useful determinations were made based on the analysis performed in the "Outcomes based on Goals" and "Outcomes based on Launch Date" data far more can be determined with the available data. One crucial piece of information that could provide additional context is creating a separate line graph of the average number of contributors (backers_count). This would have the ability to confirm the suspicion as to whether seasonality on the contributor level has a large role in the success of a Kickstarter. Another visualization that would be useful would be a table showing the breakdown of successful Kickstarters versus the average donation size. This could help us determine whether a strategy of targeting average people versus organizations or wealthy individuals is a better strategy for success.
