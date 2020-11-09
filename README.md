# Toronto Housing Market
## Why are houses so expensive in Toronto? 

There has been a lot of public debate recently about housing prices in Toronto. The cost of living is becoming unaffordable for many Torontonians and home ownership has become unfeasible for a growing percentage of the population. There have been lots of explanations offered and solutions presented from across the political spectrum, yet the data underlying many of these arguments seems surprisingly scarce and the arguments surprisingly non-quantitative. 

## In under only 6 hours, the aim of this analysis is to 
1. Understand the most important cause of high prices
2. Suggest one or two policy proposals, based on the findings above, that are most likely to reduce housing prices by the largest magnitude. (Even if not actually viable in the real world)

## Description of factors and the corresponding datasets used

### Trends of Average Sale Price of houses in Toronto
What does the current housing market look like? Refer to dataset [Toronto Avg Sale Price](datasets/toronto-avgsales-avgsalesprice.csv) and [Toronto MLS House Price Index](datasets/MLS-HousePriceIndex-AllTypes-SeasonallyAdjusted-BenchmarkPrice.xlsx)

### The factors that I consider for this work are 

#### 1. Stock: Supply and Demand
Is the supply in the market meeting the demands? Is there a difference in both? 
To understand supply, we will look at the number of newly constructed houses, houses under construction and housing whose construction have started but not completed ([Supply of Houses](datasets/toronto-starts-underconstruction-completions.csv))
To understand demand, we will look at population rise ([Population of Toronto](datasets/toronto-population.csv)), 

#### 2. Real Income and Demographics
Intuitively, as people start earning more, they are able to afford buying homes instead of renting them. So we can look at median income of all household types, and how that has changed over the years. Refer to dataset [Toronto Median-Income](datasets/toronto-median-income.csv)
Under demographics, I look at age distribution of both males and females, refer to [Demographics](datasets/toronto-demographics-2011and2016.csv)

#### 3. Cost and accessibility of mortgages
For understanding lending policy, I will look at the [Canada Lending Rates](datasets/canada-lendingrates.csv)  and their trends over time.

#### 4. Construction and Development costs
What is the land cost at which the house is built? What is the cost of development, something that is usually passed on to the homebuyer? I look at [Cost of Construction](datasets/toronto-devcharges.csv)

## Follow analysis [here](https://github.com/prashansa/TorontoHousingMarket/blob/main/TorontoHousingMarket.ipynb)

