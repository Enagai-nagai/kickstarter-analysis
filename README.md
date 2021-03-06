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

* The number of successful campaigns shows a big fluctuation throughout the year, increasing from March and peaking in May, and then gradually decreasing until December.
* On the other hand, it demonstrates that the number of failed campaigns fluctuates much less than that of successful campaigns.
* The number of canceled campaigns is much more stable and it's close to zero throughout the year.

![image](https://user-images.githubusercontent.com/99149443/161326610-6095dc92-fbae-43cd-978e-b1061914db35.png)

### Analysis of Outcomes Based on Goals
* We can see that the higher the goal is the less successful the campaign gets as a general trend. It is more probable that the campaign is successful until the goal is 15000 to 19999 USD, however, it gets more likely to fail after the goal is over 20000 USD. 
* However, the graph shows a different trend for the range from 25000USD to 44999 USD, and there were more successful campaigns than failed ones when the goal was among from USD to 44999 USD.

![image](https://user-images.githubusercontent.com/99149443/161326691-c33ffc65-8f46-4837-a82a-75994aa68d55.png)

### Challenges and Difficulties Encountered
1. **The trend is not consistent over time**  
The general trend we saw in the dataset among theaters/plays from 2009 to 2017 is not always consistent if you look at the certain year.  
For example, the trend of the outcome against the launch date changes quite depending on which year you are looking at. If we see the dataset of only 2014, the trend I mentioned above doesn't remain any more.  
![image](https://user-images.githubusercontent.com/99149443/161326788-02201904-7adb-41ce-a968-80ab6742aedd.png)

It is quite important to recognize that the trend might be inconsistent by checking it year by year so we don't lead to the wrong idea.

2. **The logic behind the trend is unknown**   
Even though we can see general trends in the graphs, we don't necessarily know what is causing these trends. 
While it makes sense that it is more difficult and less probable for campaigns with a big goal amount, it is not as clear why there are many successful campaigns around May.  
It can be simply because of the people's behavior (For example, people typically have more dispensable money during the summer as they don't have to spend on Christmas gifts) or because Kickstarter probably publishes a big advertisement to boost the number of users in May.
It is quite critical to know the reason behind what we see in the data so we make good decisions.


## Results
### Conclusion
The following is recommended to make the campaign successful.
**Regarding the launch date, **
* Launch the campaign in May or close to May and 
* Avoid launching the campaign in December
**Regarding the goal amount,**
* Make the goal amount minimum (if possible less than 4999 USD, which has a high percentage of being successful)
* Half of the campaigns whose goal is above 20000 USD failed
### Limitation of the dataset
As mentioned in the above "Challenges and Difficulties", this dataset has a few limitations to making a thorough analysis
1. **Relatively small sample size**
Even though we have thousands of data points, it is still small to recognize the trend as statistically significant
2. **Lack of information that is not campaign-related**
This dataset doesn't include the information critical for our analysis, such as the number of monthly users/viewers of Kickstarter, and the marketing and promotion plan of Kickstarter. This information would give us a deeper insight.

### Other possible analyses we could create
1. **Related to launch date**
* % of the outcome against the launch date
Here we can see that the % of successful outcomes drops in December, however, it doesn't fluctuate a lot from January to November only except it peaks in May.  
![image](https://user-images.githubusercontent.com/99149443/161326831-18ea6f6c-bd3f-4b54-adeb-58ec6f313c10.png)


2. **Related to the number of backers**
* Average number of backers by the type of outcome
This graph demonstrates that the successful campaigns have acquired way more backers compared to canceled and failed campaigns.  
This indicates it is critical to expose the campaign to as many people as possible so it can earn enough backers.  
![image](https://user-images.githubusercontent.com/99149443/161326848-606ac53b-4b83-4e48-b23e-f920aaee1191.png)

