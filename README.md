# Project1_Realestate_Analysis
Property price analysis for Melbourne


Everytime when you start to work on our project:

1. cd your terminal to your local repo file
2. git pull the change from that other team members (let your local repo has the latest version)
3. update your work log in the readme file if you want to 
4. update your work into your own branch, we will merge all of them into main branch at the end. Don't push your work to main branch.




# Material

Price Factor influencing property development and purchases (real estate) - melbourne
 
Questions

1.Do purchase price and sell number and rent number impact by bank interest rate (base on quartly data and bank interest rate, line chart) -Echo

2.In three different years, compare whole number of list and sold (use sum up value, bar chart) -therese

3.Have purchases increased/decreased between 2019 - 2021 (quartly, median sell price, listing, sold) - therese? 

*4.What has caused the increase or decrease? (covid, loan interests, schools)

5.Does the quantity of the schools has anything do with the property price? Or just the quality of the schools? (heatmap of schools and heatmaps of price, heatmps of median price with markers of top ranking schools) - Rachel

6.Does the median price of the rent has relationships with price of sold?(scatter plot, linear regression) - Anjali

7.Does the list of rent has relationships with price of sold?(scatter plot, linear regression) - Anjali

8.What is the most popular suburb or type of dwelling? (heatmap-googlemap geo module, marker about school (government, catholic, private) - Rachel

9.The outliners of 2019-2021 in Highest sell price, median sold price (boxplot, maybe highlight the outliner) - Echo

 
# Hypothesis

•Covid Effect
1.Null Hypothesis - If there was no covid then the sales number and price of property would be high
2.Alternative Hypothesis - If there is covid the sales number and price of property would be low
•Bank Interests
1.Null Hypothesis - If the bank interests is drop and then the sell price of the property will go high
2.Alternative Hypothesis - If the bank interests is drop and then the rent of the property will go low
•School Ranking/Number of Schools
1.Null Hypothesis - If the school ranking is not high then sales the price of property  will be median
2.Alternative Hypothesis - If the school ranking is high then then sales the price of property  will be high

Datasets

https://developer.domain.com.au
https://onproperty.com.au/free-sites-for-property-research/
https://developers.google.com/chart/interactive/docs/gallery/geochart
https://www.greatschools.org/api/
https://developer.domain.com.au



# Echo's contribution

Using the GET /v1/addressLocators and GET /v1/suburbPerformanceStatistics/ from Domain, to find the price as follow:

MedianSoldPrice, AuctionNumberAuctioned, AuctionNumberSold, AuctionNumberWithdrawn, NumberSold, LowestSoldPrice, HighestSoldPrice, 5thPercentileSoldPrice, 25thPercentileSoldPrice, 75thPercentileSoldPrice, 95thPercentileSoldPrice, DaysOnMarket, DiscountPercentage, MedianRentListingPrice, NumberRentListing, HighestRentListingPrice, LowestRentListingPrice, MedianSaleListingPrice, NumberSaleListing, HighestSaleListingPrice, LowestSaleListingPrice

![Screen Shot 2021-06-20 at 3 37 42 pm](https://user-images.githubusercontent.com/75764401/122663398-838d8680-d1dd-11eb-944a-75ec6944c2be.png)
Clean the dataset, and save to the main branch for everyone to use.

Help setup the questions and help others with the questions several times(how to write the code(how to use the pandas and matplotlib, how to work with the github), then setup the presentation frame.
Finish the part of fundamentally analysis of the property market in Melbourne and also the Covid impact and Bank interests impact.

# Rachel's contribution: 
Can consider this API, we can specify the stats based on quarter or year, and specify the region, it still provide majorities of the stats infor that we requires.
https://developer.domain.com.au/docs/latest/apis/pkg_properties_locations/references/suburbperformancestatistics_get

using python to map geo graph data
https://towardsdatascience.com/mapping-geograph-data-in-python-610a963d2d7f

https://plotly.com/python/box-plots/

Therese supplied
school list and list of popular suburbs

updated google generate docs summarize project details

17 june via slack
https://www.land.vic.gov.au/valuations/resources-and-reports/revaluation-2020-outcomes

21 june via slack
https://www.rba.gov.au/chart-pack/interest-rates.html
