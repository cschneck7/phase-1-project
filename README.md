# phase-1-project

<!--
Author: Carl Schneck

Welcome to my Data-Science Phase 1 project for Flatiron Academy!

It is a market analysis on films to help an imaginary client at Microsoft, whom is interested in adventuring into the film industry after seeing other big companies success. This projects focus is to analyze a movie review database and help microsoft make an educated decision on the direction they should take to be succesffull in the industry of film making. I'll be utilizing basic statistical analysis and visualizations to give three recomendations. These will be a part of a five to ten minute non-technical presentation given to a Microsoft stakeholder role being played by one of Flatiron's instructors. A jupyter notebook will also be utilized to explain my process on the back end to achieve these results.
 -->
<!-- 
The results of this analysis was the suggestion of three different genre pairings. The Three pairings are listed below:

1.Sci-Fi and and Thriller
2.Sci-Fi and Adventure - Blockbuster
3.Animation and Action - Blockbuster

I came to these suggestions by analyzing the availabe monetary data. I chose to concentrate on monetary data because I feel like the financials are most important to keep the studio running and able to work on more projects. Therefore using the gross revenue and production budget data available in the datasets provided I was able to estimate the marketing costs and adjusted gross revenue that the film studio will actually realize. These figures were found on a website Stephen Follows in the two articles linked below.

https://stephenfollows.com/how-movies-make-money-hollywood-blockbusters/
https://stephenfollows.com/films-make-money-pt2-30m-100m-movies/

It was found from these articles that the film studio only actually realizes 53% and 41% of the films Domestic and International Gross Revenues respectively. It was also estimated that each film incurred a marketing costs of 81% of production budget if it's production budget was greater than $100 million, and a marketing cost of 100% to 120% of production budget if the production budget was between $30 and $100 million. Using these factors I was able to determine what revenue a film needed to reach in order to be profitable. Using this figure I analyzed genre pairing success rates, Percentage on Investment (POI) and the correlation between production budget and POI. The three suggestions were then decided using these three metrics. -->

## Introduction:

Microsoft has a newly found interest in creating their own original video content and are moving forward by starting their own movie studio. The question to be explored is what direction Microsoft should pursue to make sure they are on a pass to success. There are two versions of success to possibly be pursued. Making sure to create a film that is highly rated, and or one that performs greatly in the box office assuring a profit on the expendtiure. While it would be ideal for both of these to happen coincidingly it may not always be possible. For instance a film may have a very high rating, but be stuck in a niche market and not have exceptional performance in the box office. For instances like this it may be better to concentrate on ensuring a positive return on the financial investments. By trying to ensure a profit the film studio can continue to pursue more films as realize a return on their investment. Therefore this analysis will concentrate on the monetary factors instead of ratings to determine the correct path for Microsoft.


## Goal:

The overall goal for this analysis is to lead Microsoft on a successful journey into making their own original video content. This will be achieved by supplying Microsoft with three actions that will give them the highest chance of success.


## Business Understanding and Method

Now what monetary factors need to be considered to determine a profitable film. Each film has different revenue streams as well as expenses. The resources available permit the use of box office revenues, as well as production budget for expenses. Some research from the links below give insight on what percentage the film studio actually realizes after taxes and the cinema's get their share. This source of information also supplied a guideline to calculate the marketing costs in relation to production budget for films with a production budget greater than $30 million. Since this information was only available for films in that production range, those will be the only ones included in this analysis. Though a brief analysis showing why it is dificult to analyze those films without that information will be made. Analyzing these details will give a reasonable answer to what determines a film to be profitable.

[How movies make money: $100m+ Hollywood blockbusters](https://stephenfollows.com/how-movies-make-money-hollywood-blockbusters/)
[How films make money pt2: $30m-$100m movies](https://stephenfollows.com/films-make-money-pt2-30m-100m-movies/)

The information regarding marketing costs and adjusted gross revenues for cinema shares and taxes acquired from these articles is listed below.

- Average Domestic Gross Revenue Realized =~ 53%
- Average International Gross Revenue Realized =~ 41%
- Marketing Costs =~ 81% Production Budget (Production Budget >= \$100 Million) 
- Marketing Costs =~ 100% to 120% Production Budget (Production Budget Between \$30-\$100 Million) 

Therefore a film is determined to be profitable if:

(Adjusted Domestic Gross Revenue) + (Adjusted Internation Gross Revenue) > (Production Budget) + (Marketing Costs)

Where Adjusted Gross Revenues are the box office revenue figures provided adjusted to take out the percentage taken from Taxes and Cinema Shares.
    
Now that the definition of a profitable film has been made, movie genres that will ensure the best chance to succeed will be researched. First genres will be looked at seperately followed by an analysis of genre pairings. The success rate, average Percentage on Investment (POI), and correlation between Production Budget and POI will be used to determine the best genres and pairings. Groups with high success rates and average Percentage on Investment will be placed on the top of the list. While groups with either high or no correlation between production budget and POI will be considered. High correlation will be considered because it gives an easily manageable metric that is directly related to the return on investment. Groups with no correlation will also be considered if the grouping meets the other two conditions. Reason being that no correlation will show that the risk can be limited by not requiring a expense line.






























