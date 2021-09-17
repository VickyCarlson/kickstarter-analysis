# Kickstarting with Excel

## Overview of Project

This project was based on data accumulated over nine years from a variety of countries and categories. Louise’s play, *Fever*, came close to being fully funded, but was not successful. This project analyzed data from other fundraising campaigns in Excel to determine if a different fundraising strategy might help Louise achieve a more successful campaign. I analyzed the outcomes of fundraising campaigns in the theater category to see what the effect of the launch date had on the success of the campaign. I also did an analysis of the outcomes of the campaigns based on the goal amount of the campaign to see if donation amount had an effect on the outcome so that Louise could make different decisions in future endeavors. Several Excel skills were used to complete the analysis. Some of the skills included conditional formatting, filters, pivot tables, VLOOKUP and COUNTIF formulas, formulas to account for measures of central tendency and spread, and charts to visually portray the analysis of outcomes based on launch date and outcomes based on goals.

### Purpose

The purpose of this analysis is to determine what the effect of launch date and funding goals had on the success of a fundraising campaign. Because Louise’s play came close to achieving the fundraising goal, but was not successful, she would like to know if the launch date or amount of the fundraising goal for other plays affected the outcome of the success of the campaign. Based on this analysis Louise could use this information to evaluate different strategies to have a higher probability of achieving a successful fundraising campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

By analyzing theater outcomes based on launch date, it appears that the best months to launch a fundraising campaign are May and June, with July numbers still showing a good success rate. The highest amount of campaigns overall occurred in each of these three months, and the greatest number of **successful** campaigns were launched during those months. Even though the number of **failed** campaigns also increased slightly during those months, the increase was very modest compared to the much higher increase in successful campaigns. 


The peak month to start a campaign was in May. The greatest number of successful campaigns occurred during May (111), followed by June (100) and then July (87). Other than a slight uptick in October (65), successful campaign numbers dropped steadily every month after May until January. December was the least successful month to launch a campaign, with only 37 successful and 35 failed campaigns.

![Theater_Outcomes_vs_Launch.png](/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

The theater campaign was further broken down into the subcategory *plays* for analysis. There were three possible outcomes for this subcategory: successful, failed and canceled. There were no plays in the canceled category for this subcategory, so the line on the chart is shown on the 0 axis for the plays category. 

The highest percentage of successful campaigns were for the campaigns with fundraising goals less than $1000 (75.81%) and from $1000 to  $4,999.00 (72.66%). The actual numbers for the successful campaigns were also highest in this range. Campaigns with fundraising goals from $35,000.00 to $44,999.00 also had a high rate of success (66.67%), although the actual count of campaigns in this range was small. If the number in a specific category is small, the result may be skewed to look more or less successful simply because a small change in the count can create a great change in the percentage.

The highest chance of failure for fundraising campaigns were those with a goal between $45,000.00 and $49,000.00 (100%). This, however, is an example of how a small count can make a large percentage change. Since there was only one campaign in this category, and it failed, 100% of the campaigns with this fundraising goal failed. Campaigns greater than $50,000.00 also had a high failure rate (83.33%), and campaigns with goals from $20,000.00 to $34,999.00 also had a lower chance of success.

![Outcomes_vs_Goals.png](/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

The greatest challenge was the actual analysis of the data to find reasons why certain fundraisers were more successful than others. Using a box and whiskers chart to find outliers helped to show greater clarity because when the outliers were removed, the mean fundraising goal was much different than when the outliers were included in the results. 

Working with the Excel file itself was not difficult; however, the box and whisker plot and some of the measures of central tendency were new concepts, i.e., IQR. The measures of central tendency, however, are important in determining what the general tendencies in a dataset are.

Another challenge in working with the data was that the data was presented in raw format. Rather than having familiarity with a business and processes, the data was analyzed with very little background. Because of this, conclusions could be off because of a misunderstanding of the reasons for some of the data presented. It is best to have a full understanding of the details of the data, but it is not always possible.

## Results

**- What are two conclusions you can draw about the Outcomes based on Launch Date?**

* The most successful months to launch a fundraising campaign are May through July.

  One hypothesis for the success of the campaigns from May through July is that campaigns that were created in the summer had better success since people take vacations in the summer. In addition, children are out of school and families can enjoy going to the theater. Campaign success dropped until a small uptick in October, when some families have a fall break scheduled, but the failures were also high in October. 

* The least successful month to launch a campaign is December. 

  Campaigns that started in December were not successful, possibly because during the holidays there are many other activities that occupy people’s time. In addition, finances are stretched for holiday purchasing, so people may not choose to pledge funds during December.

**- What can you conclude about the Outcomes based on Goals?**

Overall, if the goal of campaigns is below $4999.00, the chance of success is high. Conversely, as the goal increases, the chance of failure increases. 

The table may show a more precise picture of the data than the graph. In the graph, the comparison of successful campaigns to failed campaigns is calculated by comparing the percentage of successes and failures within each goal category, i.e., percent of successes compared to percent of failures within campaigns under $1000, then goals between $1000 and $4999, etc. As the goal amount increases, the sample of data within each category becomes smaller, so a small number in either the success or failure category may show a dramatic percentage change. In the goal category between $45,000 to $49,999, there was only one campaign, so the outcome could only be 100% or 0%. In this case the campaign failed, so the percentage failed was 100% and successful was 0%.

**- What are some limitations of this dataset?**

1. One of the limitations of the dataset is that it contains older data that may not be as relevant as more current data. The dataset spans nine years, from 2009-2017. More current data could provide more accurate costs. In addition, there may have been factors that would skew the data, such as economic downturns (or upturns), weather phenomena, etc., that might affect the success of fundraising goals

2. Another limitation in the dataset is that there are a wide variety of categories that may not be comparable to each other. The more the data has similar characteristics, i.e., the same subcategory, the more valuable the results will be. 

3. Depending on what specific data is analyzed, some analyses may not be as relevant between countries. Cultural values, economic data and other factors could affect the analyses.

4. Even though the category of plays seems to consolidate the data into a dataset that has similar characteristics, there might be other factors that could cause a play not to be funded other than the goal. For instance, the topic of the play might play a large role in why the play was not funded. 

**- What are some other possible tables and/or graphs that we could create?**

Following are some examples of other tables and graphs that could be created within this dataset:

1. Pivot chart and table of the percentage difference between the goal and the amount pledged. The difference in many failed campaigns was very small.
2. Pivot chart and table showing the average length of time between the start and end of a campaign by successful and by failed campaigns.
3. Pivot chart and table comparing the subcategory *Plays* for successes and failures based on country.
4. Pivot chart and table comparing the average donation by country.
5. Pivot chart and table analyzing the success and failures of campaing funding for certain types of plays, i.e., comedies, one-man shows, drama, etc. The dataset does not currently contain this data; however, it would be interesting to see if the type of play had an effect on its success.
6. Pivot chart and table of the successes and failures by year.
7. Pivot chart and table of the average goal by year.





