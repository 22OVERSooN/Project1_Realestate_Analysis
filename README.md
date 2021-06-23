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
School Ranking/Number of Schools
1. Null Hypothesis - If the school ranking is not high then sales the price of property the will be median.
2. Alternative Hypothesis - If the school ranking is high then it will increase the sales price of the houses

Covid Effect
1. Null Hypothesis - If there was no covid the sales of property would be high and pricing 
2. Alternative Hypothesis - If there is covid property sales would be low and pricing would be high


look at housing market
during covid
found changes sales %
impact would need further research

Datasets

https://data.melbourne.vic.gov.au/Property/Development-Activity-Monitor/gh7s-qda8
(Can only get the data of longitude, latitude and address)

https://data.melbourne.vic.gov.au/browse?category=Property&sortBy=most_accessed&src=fpc&tags=property
https://data.melbourne.vic.gov.au/Property/Properties-leased-by-City-of-Melbourne/3v7r-q3ds
https://developer.domain.com.au
https://onproperty.com.au/free-sites-for-property-research/
https://developers.google.com/chart/interactive/docs/gallery/geochart
https://www.greatschools.org/api/


Australian census
Reserve bank - interest rate?
Location of schools -
 post code map
 heat map /highest prices -flag top high school/ list school
Highest lowest areas with schools median house price
Compare property price with development
Investigate influence of covid which increased purchase or rental rate
Compare house sale time overtime vs interest rates offered
Compare house types
Purchase vs rental
Purchase purchase vs ranking


# current dataset Echo find
By using the GET /v1/addressLocators and GET /v1/suburbPerformanceStatistics/ from Domain, we will be able to find the price as follow:

MedianSoldPrice, AuctionNumberAuctioned, AuctionNumberSold, AuctionNumberWithdrawn, NumberSold, LowestSoldPrice, HighestSoldPrice, 5thPercentileSoldPrice, 25thPercentileSoldPrice, 75thPercentileSoldPrice, 95thPercentileSoldPrice, DaysOnMarket, DiscountPercentage, MedianRentListingPrice, NumberRentListing, HighestRentListingPrice, LowestRentListingPrice, MedianSaleListingPrice, NumberSaleListing, HighestSaleListingPrice, LowestSaleListingPrice

![Screen Shot 2021-06-20 at 3 37 42 pm](https://user-images.githubusercontent.com/75764401/122663398-838d8680-d1dd-11eb-944a-75ec6944c2be.png)

# Rachel's suggestion: 
Can consider this API, we can specify the stats based on quarter or year, and specify the region, it still provide majorities of the stats infor that we requires.
https://developer.domain.com.au/docs/latest/apis/pkg_properties_locations/references/suburbperformancestatistics_get

using python to map geo graph data
https://towardsdatascience.com/mapping-geograph-data-in-python-610a963d2d7f

https://plotly.com/python/box-plots/
