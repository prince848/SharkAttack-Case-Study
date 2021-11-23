# SharkAttack-Case-Study
Data wrangling, cleaning, and manipulation with Pandas of a messy dataset. The data for this case study and analysis is a publicly available data set that was downloaded from the Global Shark Attack File, located here:
https://www.sharkattackfile.net/incidentlog.htm

Ocean temperatures were also explored with this dataset:
http://app01.saeon.ac.za/sadcofunstuff/OceanTemperature.htm

In this readme, I will provide a summary of the data cleaning process and the analysis performed. In the jupyter-notebooks in the folder named "your-code" it is listed step by step all the processes related to this project.

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
google sheet file [Probability of a shark attck per month at a specific location](https://docs.google.com/spreadsheets/d/1iMG16n99fP-HJ9bOfDyxXg9TdrTcnU8aMio3eWB1Geo/edit?usp=sharing)

