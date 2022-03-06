# Kickstarting with Excel

## Overview of Project
This project looks at different fundraising campaigns and the success of each campaign against their funding goals based on their launch date.  

### Purpose
The purpose of this project is to understand to review (1) theatre parent category success rate based on launch date; and (2) play subcategory success rate against funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For Analysis of Outcomes Based on Launch Date, I created a pivot table of all successful, failed and canceled theatre campaigns by month and then made a chart [(https://github.com/legeren/kickstarter-analysis/blob/33429fc6574d6e689bae91bb7f42c21fef323bda/resources/Outcomes_vs_Goals.png)] to visualize the success rates based on month.

### Analysis of Outcomes Based on Goals
For Analysis of Outcomes Based on Goals, I created a table counting all successful, failed and canceled plays per different funding thresholds and then made a chart [(https://github.com/legeren/kickstarter-analysis/blob/33429fc6574d6e689bae91bb7f42c21fef323bda/resources/Outcomes_vs_Goals.png)] to visualize the success rates based on funding thresholds.

### Challenges and Difficulties Encountered
For Outcomes Based on Goals analysis, I originally neglected to include the fourth criteria to the countifs function which resulted in miscalculation of total number of plays.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
(1) May and June are the most successful months to launch campaigns; (2) Funding campaigns in December have a 50/50 chance of succeeding/failing (therefore, recommendation is not to initiate funding campaigns in December).

- What can you conclude about the Outcomes based on Goals?
Majority of plays (1,530) require only $20K or less of funding.   Of this, there is a 59% average success rate to reach its funding goals.

- What are some limitations of this dataset?
Limitations for this dataset include (1) it does not include information on the backers--e.g., are females more likely to support plays vs males?; (2) there is a subcategory under theatre parent category called "spaces" which is unknown and may fall under different formats or genre which we could further analyze; and (3) the rationale behind the start and end date of each funding campaign might be useful for additional analysis as some campaigns stretch out to a couple of months while others only last a couple of weeks

- What are some other possible tables and/or graphs that we could create?
We could also (1) compare all subcategories under theatre parent category to see whether plays are more successful or not against other subcategories; (2) compare if the same results are true for all geographies by reviewing results per country; (3) for outcomes based on launch date---review year over year comparison to see if all years follow the same trend; and (4) further reviewing how many backers are behind each play to make it successful.
