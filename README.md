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
The data cleaning and analysis part in python is uploaded above
