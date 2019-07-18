# Investigate the FBI gun permit dataset
The purpose of the project is to investigate the data from the FBI's National Instant Criminal Background Check System. This system is used by gun shop to ensure that the prospective customer does not have a criminal background and is eligible to purchase a firearm. Additional information at the state level is also provided by a dataset from [census.gov](https://www.census.gov/).

> It is important to note that although background checks for firearms are correlated to gun sales, as stated in the [FBI NICS Firearm Background Check Data](https://github.com/BuzzFeedNews/nics-firearm-background-checks/blob/master/README.md), that there is no 1 to 1 correlation, due to several factor such as sales without background check (https://www.thetrace.org/2015/10/private-sale-loophole-background-check-harvard-research/) and state regulations that might require periodic background check for gun owners. For the purpose of the project we will only focus on the number of gun-related background checks instead of trying to estimate which background check led to an actual purchase of firearm.

## Files used
* gun_data.csv
* US_census_data.csv

## Requirements
* python 3
* Jupyter notebook

## Workflow

### Data wrangling
* **First section** The purpose have a general understanding of the data contained in the two databases, and identify how to clean the data to prepare it for further analysis.
* **Second section** In this second section of the Data Wrangling part, the issues found in the 'General Properties' section will be addressed in order to clean both dataset so they will be ready for further investigation. 

### Exploratory data analysis
* The purpose of this section is to answer significant quetions such as:
1. #### Which state had the highest number of gun-related background checks in 2010 and 2016? Which state had the lowest?
2. #### How does the number of gun related background checks change overtime?
3. #### How does the number of background checks changes based on different demographic factors such as sex, race, etc.?

### Conclusions
* This section summarizes the findings such as the rate of increase of background checks in the recent years, the distribution nationwide and the relation to demographic factors. This section also discusses the results taking into account additional data pertaining to state regulations of background checks.
