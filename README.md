# Kickstarting with Excel

## Overview of Project

Lousie is raising fund through a wide variety of campaigns including theater plays, film and videos, and food with different launch time and various goals.This project is to uncover how fund raising outcomes of a specific category theater campaign vary based on their dates and goals. I will firstly find theater data from the kickstater dataset and group them by their launch datas and their funding goal amount perspectively, and visualize the data through line charts to see the trends. The project will include analysis, challenges, results, limitations, and suggestions for further analysis.

### Purpose
All theater campaign outcomes can be grouped into sucessful, failed, canceled, and live. And the outcomes may be related to their launch dates and funding goals.The purpose of the project is to explore how launch dates and funding goal amounts will effect outcomes of theater fund raising campaigns. Based on the analysis, data-driven results will be delivered to suggest better launch dates and more reasonal funding goals for theater campaigns.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I created a pivot table and filtered data based on their parent category "theater" and their monthly launch dates. According to the chart and the table, there are 839 successful theater campaigns, 493 failed theater campaigns, 37 canceled theater campaigns. Apparantly, from April to August, successful campaigns are over 70. And there is a peak of successful campaigns in May, that is 111. While in December, there are only 37 successful campaigns. 

![Outcomes based on launch dates](https://github.com/ZiwenLyu/-kickstarter-analysis/blob/main/screen%20shot%20based%20on%20launch%20dates.png)


### Analysis of Outcomes Based on Goals
I created an another table to view the campaigns of plays with differnt outcomes and their proportions. I created the goal amount range which is from the less than 1,000 dollars to the greather than 50,000 dollars, each group increases by 5,000 dollars, and I finally got 12 groups of plays campagins based on their goal amounts. According to the chart and the table, most goal amounts of campaigns of plays are under 10,000 dollars. From less than 1,000 to 19,999 dollars, there is a slow decrease in successful percentage from nearly 80% to 50%. And campaigns with goals of 20,000 to 34,999 dollars, and greater than 45,000 dollars have more failed ones than sucessful ones. 

![Outcomes based on goals](https://github.com/ZiwenLyu/-kickstarter-analysis/blob/main/screen%20shot%20based%20on%20goals.png)

### Challenges and Difficulties Encountered
In the analysis, I have difficultiy to read the data and derive my own conclusions. And I cannot stop thinking why the data will look like that. For instance, the lines of failed and successful campaigns based on goals do not constantly go up or down but fluctuat. It takes me some time to figure out and find an explanation for that. One reason I find is that it's because this is the percentage we are analyzing so the chart cannot reflect the size of total project bases. And that's something we will need to consider when choosing the suitable charts to see results. 

## Results

- Two conclusions drew from the Outcomes based on Launch Date: (1) Theater campaigns are likely to be more successful if they are launched in warmer months (Apr, May, Jun, July, Aug). (2) Failed theater campaigns are likely to have a constant count from 30 to 50. 

- One conclusion from the Outcomes based on Goals: campaigns of plays with lower funding goal amounts are more likely to succeed.

- Some limitations of this dataset: Some live campaigns are not included in the analysis, so the analysis might be different with new data. Also, in analysis of outcomes based on goals, there are some outliers with much more goal amounts make the line fluctuate a lot.

- Some other possible tables and/or graphs that we could create: In the outcomes based on goals analysis, we can create a bar chart based on the counts of successful, failed, canceled instead. The bar charts of outcome counts can clearly showing which goal amount range has most successful plays campaigns and we can easily compare successful and failed counts in each range.
