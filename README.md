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

# Schools analysis
Questions to answer:
1. Does number of schools (in a suburb) and rankings of schools impact on: 
--property sale price 
--property sale activities (number of houses sold in a suburb) 
2. Is there relationship between suburbs where the property get sold the most and suburbs where the top ranking schools locate.

Method: --Scatterplot to show case the relationship between the schools spread (locations) and the School count under each postcode --Scatterplot to show case the relationship between the schools spread (locations) and the house median sold price under each postcode --Gamps heatmap to indicate the median sale price among greater Melbourne regions --Gamps symbol to indicate suburbs which has the most houses sell activities --Gamps symbol to indicate suburbs which has the most houses sell activities --Gamps marker to indicate top ranking schools among greater Melbourne regions

Conclusions: 
From the scatter plots, we can see the median sale price is lower around the outer part of Melbourne region, and gradually increase towards the centre part of Melbourne . We can also see from the map that the majorities of the top ranking schools are located towards the centre part of the Melbourne. Hence we believe there is correlation between schools’ ranking and the property sale price. Where there are high ranking schools, the property sale price would be boosted. 

However, from the scatterplot the numbers of schools in a suburb does not appear to have a positive impact on suburbs, we can see from the plot, where there are the most schools, the suburbs have rather low median sale price. 

From the heatmap we can tell how the sale price spread cross the greater Melbourne region. On top of the heatmap, the symbol layer indicates the suburbs appear to have most sold properties. And the makers flag the top ranking schools. However, we can see there is not much overlapping between the suburbs has most sale activities and the suburbs has highest ranking schools. Saying that, it might also due to the fact that majorities of top ranking schools are located in the area that too expensive to purchase, and people opt to rent instead. However, to determine that, we need to analyse further and combine other factors as well.
![map (2)](https://user-images.githubusercontent.com/82508049/123532263-19319480-d74f-11eb-82bd-fe5a6dd00088.png)
