# kickstarter-analysis
## Overview of Project
### Background
Louise is planning to launch her play "Fever" by raising funds with crowdfunding at "Kickstarter" platform.
"Fever" project reached close to its goal in a short amount of time.
### Purpose
This analysis is conducted to explores how (1)launch dates and (2)goal amounts relate to funding outcomes by using the data of "Kickstarter" previous campaigns so Louise understands the trend and get insight on how successful her project can be.

## Analysis and Challenges
Explain how you performed your analysis using images and links to code, as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered.

On order to prepare this report, I used the dataset of previous camipaigns at Kickstarter platform, which includes 4114 campaigns launched from 2009 to 2017.

### Analysis of Outcomes Based on Launch Date
For this analysis, I focused on only parent category "Theater" to see a more defined trend.

* The graph shows that the number of successful campaigns increases from March and peaks in May, and then gradually decreases until December.
* On the other hand, it demonstrates that the number of failed campaigns fluctuates much less that of successful campaigns.
* The number of canceled campaigns is much more static and it's close to zero through out the year.

![Theater_Outcomes_vs_Launch](https://github.com/Enagai-nagai/kickstarter-analysis/blob/main/Images/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
For this analysis, I focused only subcategory "plays" to see a more defined trend.
* We can see that the higher the goal is the less successful the campaign gets as an overall trend. It is more probable that the campaign is successful until the goal is 15000 to 19999 USD, however, it gets more likely to fail after the goal is over 20000 USD. 
* However, the graph shows the different trend for the range from 25000USD to 44999 USD, and there were more successful campaigns than failed ones when the goal was among 35000 USD to 44999 USD.

![Outcomes Based on Goals](https://user-images.githubusercontent.com/99149443/160183310-5a650c94-6072-452f-8e66-4528f37860c4.png)

### Challenges and Difficulties Encountered
1. The trend is not consistent over time
The overall trend we saw in the dataset among dataset of theaters/plays from 2009 to 2017 is not always consistent if you look at the certain year.
For example, the trend of the outcome against the launch date changes quite depending on which year you are looking at. If we see the dataset of only 2014, the trend I mentioned above doesn't remain anymore.
![image](https://user-images.githubusercontent.com/99149443/160216391-ea13a0d8-b7b6-487f-9f60-93a658238f47.png)
It is necessary to recognize that the trend might be inconsistent by checking it year by year so we don't lead to the wrong idea.
2. The logic behind the trend is unknown 
Even though we can see overall trends in the graphs, we don't necessarily know what is causing these trends. 
While it makes sense that it is more difficult and less probable for campaigns with big goal amount, it is not as clear why there are many successful campaigns around May. 
It can be be simply because of the people's behavior (For exmample, people typically have more dispensable money during the summer as they don't have to spend on Christmas gifts) or because Kickstarter probably publishes a big advertisemen to boost the users in May.
It is quite critical to know the reason behind what we see in the data so we make good decisions.
4. (Relatively) small samples to determine the trend
5. 

## Results
What are two conclusions you can draw about the Theater Outcomes by Launch Date?
What can you conclude about the Outcomes based on Goals?
What are some limitations of this dataset?
What are some other possible tables and/or graphs that we could create?
