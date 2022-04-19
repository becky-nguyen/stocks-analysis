# stocks-analysis

##Project Overview

The purpose of this analysis is to recommend other stocks for Steve's parents since their original investment in DQ may not have been the best choice. In this project, analyzed data on stocks from the years 2017 and 2018. We ran an original script and a refactored script for Steve to use. 

##Results
While 2017 looked to be a positive year for DQ and many other stocks, 2018 showed how important it is to properly analyze results for more than one year before making any decisions. 

###Best Stocks

![VBA_Challenge_2017](https://user-images.githubusercontent.com/100896787/164083754-f2648fcd-ee72-42c3-8551-e1489eefb018.PNG)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/100896787/164083744-0a66ca9e-afad-4fe1-9491-d9ffbf52a9f8.PNG)
In these images, we can see that in 2018, most stocks showed a great loss, including DQ despite how successful it was in the previous year. If Steve's parents were to consider investing in other stocks, we would recommend either ENPH or RUN instead, since they both showed two years of great return. If they only wanted to concentrate on one, we would recommend ENPH over RUN, as it showed even larger results (129.5% and 81.9%), whereas RUN showed steady growth (5.5% and 84.0%). Additionally, it would be best for Steve to run an analysis on prior years such as 2016 and 2015 to help make a better decision. 

###Original vs. Refactored

If Steve decides he would like to use this code to run on additional years of data, if he is strapped for time and would like the analysis faster for comparisons, he should be using the refactored code. If he were to pull data from an entire decade, for example, it would be more efficient to use the refactored script. These images below show the time difference between the 2017 original code and the 2017 refractored: 


![VBA_Original_2017](https://user-images.githubusercontent.com/100896787/164085591-7e7a51b7-6175-4c2f-936e-5274e5d2a617.PNG)
![VBA_Challenge_2017](https://user-images.githubusercontent.com/100896787/164085608-0bf5e72e-e509-4118-b350-a60d57a7ad4a.PNG)

The refactored code definitely rusn faster. However, if Steve decides there were other things he wanted to analyze and would like to change up the code, I would recommend the original. While the original does take longer to run (about half of a second longer), it may be easier to for him to comprehend it as it runs through each field (total volume, starting price, and ending price) separately by each ticker and row, whereas the refactored code utilized a tickerIndex as an index to access the fields, which could possibly confuse him if he were to make any changes. For somebody that may not be as skilled, I wouldn't recommend the refactored code. 


