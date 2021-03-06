# Module Challenge 1 -- Kickstarter Campaign Analysis
Brief analysis of Kickstarter data to uncover trends for a client interested in pursuing a campaign to fund a play performed as part of the Module 1 Challenge.
## Overview of Project
The client sought to run a Kickstarter campaign to fund the production and staging of a play. She solicited assistance interpreting existing Kickstarter data of other similar projects to determine whether launch date and the level of financial goal of other similar projects had any systematic effect on success. 
## Analysis and Challenges
The analysis determined that campaigns launched in late spring through summer were most successful with 2/3 of May and June launches succeeding. Those were also the only two months with 100 or more campaigns, suggesting that outdoor productions account for some percentage of successful launches. Average success rate by month was just over 61%, only one month (December) dipped below 50%, and the standard deviation was 4.4%, so better and worse times to launch a campaign exist, but much of the year is relatively tightly clustered around the mean.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/78886925/108564877-cee86480-72d1-11eb-9332-7c2a4feccf36.png)

The data on successful campaigns by goal provides additional insight on the types of successful play campaigns. First, 20% of campaigns sought less than $1000 and 56% of campaigns had aimed at more than $1000 and less than $5000. The success rates for both were around three-quarters, but beyond that the success rates drop to around half before success rates in aggregate dip below 50% for projects seeking $25,000 or more.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/78886925/108564675-7dd87080-72d1-11eb-823d-828db05462e9.png)

In regard to challenges, I was able to conduct the analysis per the instruction given in the Module 1 Challenge and found no difficulties that prevented successful completion of the task. The COUNTSIF function was a little tricky in that I had to experiment with finding the correct way to express two financial criteria per range for all but the highest and lowest rows (Row 2 and Row 13).
## Results
As suggested above, the best time to launch a play-focused Kickstarter campaign is from May to July. The worst time to launch such a campaign is in November to December. However, a key limitation of this data is that it does not distinguish on setting or venue of play; outdoor productions might be overrepresented in the successful launches. Additionally, the end of the year is when many individuals make charitable contributions for tax purposes, limiting the money they have available for other, non-charitable purposes.

The data on outcomes by goal provide clear results that low to moderately priced campaigns have a bigger chance of success. This implies that potential contributors are either more interested in having a larger effect on campaigns by aiming their money at lower "asks" or they believe that large productions seeking Kickstarter support have not successfully found more traditional sponsors. Without qualitative understanding of the data, which only provides a small blurb about each campaign, we cannot be completely confident in this result except to suggest "plausibility is fundability."

As noted above, further refinement of the data on venue would help answer the question of whether contributors distinguish between outdoor summer productions versus indoor productions. It would also be worthwhile to provide another category of data on the type of production beyond musical or non-musical to further categorize by comedy, drama, original produciton, or adaptation. With data like that, we could we more confident in providing advice to our client. 
