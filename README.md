# Facebook-Ads-Targeting

In Class Case

Problem: 
1. identify targets for which advertisements the organization should extend.
2. How to appeal younger customers in targeted ads?

Data Dictionary:
- date: to the week the advertising campaign was run,
- adType: refers to whether the advertisement appeared in a link or a photo post
- category: refers to the type of retailer referenced in the advertisement
- placement: represents whether the ad appeared on the desktop or mobile client
- keyword: is a categorical variable that represents which store the purchase was made at
- body: represents the actual text of the ad
- ageMean: represents the average age of the targeted consumers
- clickPerDollar: represents the number of clicks the ad achieved for each dollar spent

In the original datasets, we also use two new column which is score and extend.
Score = Value/Dollar = clickPerDollar*0.006(average margin revenue of per click)/$1
The ads can be extended when return is over or equal to 10%, which means score need to be over and equal to 1.1.

