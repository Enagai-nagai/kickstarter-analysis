# Kickstarter-analysis
## Overview of Project
### Background
Louise is planning to launch her play "Fever" by raising funds with crowdfunding on "Kickstarter" platform.  
"Fever" project reached close to its goal in a short amount of time.
### Purpose
This analysis is conducted to explore how **(1)launch dates** and **(2)goal amounts relate to funding outcomes** by using the data of "Kickstarter" previous campaigns so Louise understands the trend and gets insight into how successful her project can be.  
The analysis focuses only on the Parent category "Theaters" or the subcategory "plays" as Louise's campaign is for her play.

## Analysis and Challenges
In order to prepare this report, I used the dataset of previous campaigns on the Kickstarter platform, which includes 4114 campaigns launched from 2009 to 2017.

### Analysis of Outcomes Based on Launch Date
For this analysis, I focused on only the parent category "Theater" to see a more defined trend.

* The graph shows that the number of successful campaigns increases from March and peaks in May, and then gradually decreases until December.
* On the other hand, it demonstrates that the number of failed campaigns fluctuates much less than that of successful campaigns.
* The number of canceled campaigns is much more static and it's close to zero throughout the year.

![Theater_Outcomes_vs_Launch](https://github.com/Enagai-nagai/kickstarter-analysis/blob/main/Images/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
* We can see that the higher the goal is the less successful the campaign gets as an overall trend. It is more probable that the campaign is successful until the goal is 15000 to 19999 USD, however, it gets more likely to fail after the goal is over 20000 USD. 
* However, the graph shows a different trend for the range from 25000USD to 44999 USD, and there were more successful campaigns than failed ones when the goal was among from USD to 44999 USD.

![Outcomes Based on Goals](https://user-images.githubusercontent.com/99149443/160183310-5a650c94-6072-452f-8e66-4528f37860c4.png)

### Challenges and Difficulties Encountered
1. **The trend is not consistent over time**  
The general trend we saw in the dataset among theaters/plays from 2009 to 2017 is not always consistent if you look at the certain year.  
For example, the trend of the outcome against the launch date changes quite depending on which year you are looking at. If we see the dataset of only 2014, the trend I mentioned above doesn't remain any more.  
![image](https://user-images.githubusercontent.com/99149443/160216391-ea13a0d8-b7b6-487f-9f60-93a658238f47.png)  
It is quite important to recognize that the trend might be inconsistent by checking it year by year so we don't lead to the wrong idea.

2. **The logic behind the trend is unknown**   
Even though we can see general trends in the graphs, we don't necessarily know what is causing these trends. 
While it makes sense that it is more difficult and less probable for campaigns with a big goal amount, it is not as clear why there are many successful campaigns around May.  
It can be simply because of the people's behavior (For example, people typically have more dispensable money during the summer as they don't have to spend on Christmas gifts) or because Kickstarter probably publishes a big advertisement to boost the number of users in May.
It is quite critical to know the reason behind what we see in the data so we make good decisions.


## Results
### Conclusion
The following is recommended to make the campaign successful.
Regarding the launch date, 
* Launch the campaign in May or close to May and 
* Avoid launching the campaign in December
Regarding the goal amount,
* Make the goal amount minimum (if possible less than 15000 USD)
* Half of the campaigns whose goal is above 15000 USD failed
### Limitation of the dataset
As mentioned in the above "Challenges and Difficulties", this dataset has a few limitations to making a thorough analysis
1. **Relatively small sample size**
Even though we have thousands of data points, it is still small to recognize the trend as statistically significant
2. **Lack of information that is not campaign-related**
This dataset doesn't include the information critical for our analysis, such as the number of monthly users/viewers of Kickstarter, and the marketing and promotion plan of Kickstarter. This information will give us deeper insight.

### Other possible analyses we could create
1. **Related to launch date**
* % of the outcome against the launch date
Here we can see that the % of successful outcomes drops in December, however, it doesn't fluctuate a lot from January to November only except it peaks in May.  
![Theater_Outcomes_vs_Launch_Percentage](https://user-images.githubusercontent.com/99149443/161316173-5322903a-4494-43d4-9abc-c4070ed841a6.png)

2. **Related to the number of backers**
* Average number of backers by the type of outcome
This graph demonstrates that the successful campaigns have acquired way more backers compared to canceled and failed campaigns.  
This indicates it is critical to expose the campaign to as many people as possible so it can earn enough backers.  
![Average Backer Count](https://user-images.githubusercontent.com/99149443/161319091-e2bb397f-e0db-43c9-b1ec-7143f5f7e1c1.png)

