# SharkAttack-Case-Study
Data wrangling, cleaning, and manipulation with Pandas of a messy dataset. The data for this case study and analysis is a publicly available data set that was downloaded from the Global Shark Attack File, located here:
https://www.sharkattackfile.net/incidentlog.htm

Ocean temperatures were also explored with this dataset:
http://app01.saeon.ac.za/sadcofunstuff/OceanTemperature.htm

In this readme, I will provide a summary of the data cleaning process and the analysis performed.

## Data cleaning
This dataset is very messy, but with only a few commands we can transform this file into a valuable dataset. I conducted this with a diverse set of tools in Python, as Pandas or
Regex. I identified repeated columns and others without information. I corrected typos replacing text and obtained data from columns to create others. From the reports I cleaned
the data to obtain species information when available.

Finally, there is a fraction of information that is not reliable and only introduces noise. To handle this either I labeled these unreliable datapoints accordingly or dropped it
to create a valuable and reliable dataset to visualize and analyze.
The data cleaning and analysis is done in colabs using Python and is uploaded above.
The cleaned CSV data file containing the results of data cleaning work can be found here [SharkFinal](https://docs.google.com/spreadsheets/d/1ytCxojjigYY7uCxVjRAgMfmGrsOn0ePP5CxGJy8YhK4/edit?usp=sharing).


## Data Analysis and Findings
The average shark attack victim is:
- Male
- Is an average of 27 years old. Looking at standard deviation, ages 14 to 41 as also in the high risk category
- Lives in South Africa, Australia, or the US
- Is surfing, swimming, or fishing

These are some specific examples but if the company wants to see the distribution for a different location all they must do is click on a different location on the following
google sheet file [Probability of a shark attack per month at a specific location](https://docs.google.com/spreadsheets/d/1iMG16n99fP-HJ9bOfDyxXg9TdrTcnU8aMio3eWB1Geo/edit?usp=sharing)

## Recommendation based on analysis 
- Since most shark attack victims are young men who are surfing, swimming, or fishing, marketing strategies should be targeted towards this group.  These marketing strategies should include social media and music streaming services to reach this audience.  The parents and guardians of the younger members of this cohort should also be targeted, since they are the ones most likely to purchase the Sharkbanz product.

- Corporate partnerships should be investigated with national hotels and AirBNB to focus on families traveling to beaches and who may be interested in purchasing or renting Sharkbanz for their vacation.  A break down of beaches that have a history of attacks can be found here.

- Local retailers can be partnered with to create beach gear rental packages that include Sharkbanz with the rental of a surfboard, boogie board, fishing gear, or other equipment.  This will target families visiting the area and looking for package deals to save money.

## Notes and citations
This fictional case study was inspired by other case studies in the Google Data Analytics Capstone Project.
We created this fictional case study to help "Sharbanz" a worldwide leader in shark repellent technology, creating a marketing strategy.


### Here is the link to shark attack visualization using "Tableau" : [Shark attack case study Visualization](https://public.tableau.com/app/profile/prince1103/viz/SharkAttacks_16368864906740/Story1)

### The detailed documentation of the shark attack analysis : [Documentation of results](https://docs.google.com/document/d/1K1otwPNXkCLyAajYLu0Rcln3HeVbef6_/edit#)
### Here is the report of the case study : [Report of case Study](https://docs.google.com/presentation/d/1mD-6GKxgRo3ajVTzFETIZQgZKclMVgNHeeK7ph6UEeU/edit#slide=id.gf6fba99a4e_0_756)
