# kickstarter-analysis
Module 1 Kickstarter Analysis
## Overview of Project

### Purpose

Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. 

## Analysis and Challenges

We took the data provided by Kickstarter and organized it to visualize outcomes of other plays relative to 1) Launch Date 2) Funding Goals.  


### Analysis of Outcomes Based on Launch Date
In order to visualize outcomes based on launch date we needed add a column to the data set to identify the Year as a filter for our pivot table. This allowed us to bucket the results into months independent of year a visualize any pattern of seasonality year on year. 

### Analysis of Outcomes Based on Goals
In order to visualize the Outcomes based on Goals we needed create a new sheet, create a series of ranges for the Funding Goals of those kickstarters from the play subcategory and use the countifs function bucket the successful, failed and cancelled instances of those kickstarters into those ranges.  With that data we were able to produce a line graph to visualize the outcomes based on the funding goal. 


### Challenges and Difficulties Encountered
The largest difficulty was the existence of two different data sets. At some point the data set was updated without any notification. Given to the level of difficulty of the assignment a disproportionate amount of time was spent checking and rechecking the analysis and data ss the results were far from expectations. Once the accurate data was found the difficulty was isolated to becoming familiar with GitHub to report and submit findings. 

## Results

### Conclusions of the Outcome Based on Launch Date
The visualization of the Outcomes based on Launch Date suggest two conclusions: 1. May has a much higher rate of kickstarter launches and the greatest success rate 2. December has the lowest rate of launches and the highest failure rate.   

### Conclusions of the Outcome Based on Launch Date
The visualization of the Outcomes based on Goals displays that the higher the goal the lower the success rate.  There does seem to be spike in success rate for the range 35000 to 45000 however the low number of instances in that range skew the visualization.


### Limitations on the data set 
The main limitation of the data set is detailed information on the pledges.  An average donation amount is too rudimentary to extract any conclusions on donor behavior per category.  Instead of being organized by Kickstarter ID, a data set based on Kickstarter Pledge ID that would then implicitly have all the information referring the specific kickstarter would offer a better opportunity for analysis.  

### Other possible tables and/or graphs
Other possibilities for graphs that could be relative to Louise’s inquiry include:
Outcomes Based on Duration
Outcomes Based on Average Donation
Outcomes Based on Country
Outcomes Based on Funding Goal and Launch Date 
