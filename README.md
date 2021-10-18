# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends to be able to provide Louise with recommendations on how to fundraise for her play _Fever._ 

# Kickstarting with Excel

## Overview of Project

### Purpose
Louise was fundraising for her play _Fever_ and was able to nearly hit her fundraising goal in a short period of time. The purpose of this analysis is to help Louise understand how her fundraising efforts compared to those of other campaigns using a Kickstarter dataset.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
This analysis was done by creating a pivot table and line chart to show the number of successful, failed, and canceled theater campaigns based on the month in which they began. 

Though I did not face any difficulties in this task, I imagine it could be difficult ensuring that the correct fields end up in the appropriate rows and columns in the pivot chart and making sure the correct information gets relayed onto the correct axis of the resulting chart. The good thing about pivot tables and charts is that they are highly malliable and can be played around with until you get the desired results.

### Analysis of Outcomes Based on Goals
This analysis was done by calculating the proportion of successful, failed, and canceled play campaigns based on the fundraising goal amount.

Creating the table for this analysis required use of the COUNTIFS() statement, one that I had never used before. There was much manual manipulation to ensure each row and each column showed the correct data for the columns counting the number of campaigns in each criteria bucket. I was able to copy the initial formula and pull it over for the corresponding goal buckets, which helped me save some time and energy.

### Challenges and Difficulties Encountered


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - Based on the Kickstarter data we are using, the most optimal month to launch a theater fundraising campaign appears to be May. The late spring, early summer months are also okay, but the rate of success slowly declines from May through December, so the later you go, the less likely your campaign is to be successful.
  - Based on the Kickstarter data we are using, the number of failed and canceled campaigns does not vary nearly as much as the successful campaigns. There is variance in the total number of campaigns launched by month, but the variability mostly shows in the successful campaigns, rather than in the failed and canceled ones.

- What can you conclude about the Outcomes based on Goals?
  - Based on the Kickstarter data we are using, there appears to be a largely negative correlation between fundraising goal amount and number of successful campaigns. There is an increase in successful campaigns in some of the higher amounts, however the overall trend appears to be negative.

- What are some limitations of this dataset?
  - This data is only showing data using Kickstarter. There are other platforms out there that may be better for Louise's purposes.
  - There are some outliers that exist for which we would need to decide if they are errors or legitimate data points.
  - We don't have a good understanding of what all of the columns of data are telling us, namely "staff_pick" and "spotlight."

- What are some other possible tables and/or graphs that we could create?
  - I would look at the outcomes based on launch date data, but as percentages. While whole numbers can provide good information, it may be more telling to see based on the total number of campaigns released per month, how likely is a campaign to be successful. We may see a change in what month is preferred because in this case, May also has the highest number of campaigns launch and the highest number of successful campaigns, but that may not be the case when looking at percentages.
  - There are a number of different variables that could be considered beyond just goal amount and launch date. It may be beneficial to look at things like where the campaigns are being launched or year over year data. You may also want to better understand what the columns "staff_pick" and "spotlight" mean and if they have any impact on success rates.


