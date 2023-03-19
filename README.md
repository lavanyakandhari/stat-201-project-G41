# Project Proposal
## Exploring housing prices
(by Yeojun Han, Congbo Hou, Lavanya Kandhari, Lillian Milroy)
## *Introduction*
Some of the most expensive real estate in the world is located on the California coast.[1] Over the last several decades, it has become evident that rising sea levels, climate change, and coastal erosion threaten the economic and physical stability of coastal properties.[2,3,4] Research reported by the California Legislative Analyst’s Office states that “over $150 billion of property equating to more than 6% of the state’s GDP and 600,000 people could be impacted by dynamic flooding by 2100”.[2,3]

There is disagreement among scientists, government organizations, and coastal residents about how to address the situation without sacrificing the value of at-risk properties.[1] Continued study of the relationship between property value and coastline proximity will be a useful way to gauge the efficacy of whatever measures are implemented, as well as public sentiment.

We are working with data originally collected from the 1990 California census, containing the variables longitude, latitude, housing_median_age, total_rooms, total_bedrooms, population, households, median_income, median_house_value, and ocean_proximity.

We hope to establish whether or not ocean proximity had an effect on median home value in 1990, by comparing median home prices of inland houses and houses less than one hour away from the ocean. There are extreme values present in this data, so to mitigate their impact on our results, median and IQR will be used as parameters.

The data we are using is California housing prices which can be found by going on the link provided.

## *Methods*
We are working with data from a reputable source; our data cleaning and wrangling processes are clearly elucidated, contributing to the reproducability of our results. Potential stakeholders will be able to easily understand the findings of our analysis from the plot and estimates presented; however; they are not enough to prove our hypothesis, since only descriptive analysis and no statistical inference was conducted.

Despite the boxplots, the analysis does not address how confident we are that we can accept the alternative hypothesis. To address this gap, we will utilise hypothesis testing and perform a two-sample ttest to construct a confidence intervaland obtain the range containing the true difference in median housing prices. We will also perform a repeat bootstrap analysis, and compare the results to the confidence interval.

We expect to find that the median house prices in ocean proximity are higher than the median house price inland.

Most of the currently available data regarding the relationship between ocean proximity and property value in California has focused on homes situated on or near the immediate coastline.[1] Research shows that the effects of sea level rise will extend inland beyond the coastal region, and implores policy makers to start planning more aggressively.[2,3,4,5] By using data from the 1990 census in our analysis, we hope to provide a point of reference for future study that encompasses homes outside of the traditional coastal region that still stand to be affected by the impending ecological disruption.

We can further develop the analysis by examining the impact of alternative metrics on median home prices, and perform similar analyses on recent data.
