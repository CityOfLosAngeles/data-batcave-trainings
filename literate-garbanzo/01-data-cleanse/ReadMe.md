# Identify and Remove Duplicate Records
## Utilize the Pandas library to find and remove duplicate records from a CSV file

These scripts identify duplicate records from an input CSV file based on the provided field_name and create a "clean" CSV file where duplicates are removed.

1. duplicates_find - creates a CSV file from the input file containing only the duplicate records
2. duplicates_remove - removes the duplicate records from the input file using CSV module and Pandas

Input and output files are found in the Resources folder.

### Talking Points

* Why bother examining duplicates?
* How could this process be automated? 
* What is the importance of data cleansing?
* What would be other data cleansing activities?

### TO DO

* Make process more object oriented with conditional on the ```pd.concat``` object.

### CAUTION

SFPD_CrimeIncidents_2018.csv in script was downloaded previously and is not to be taken as accurate or current

* DATA SOURCE: https://data.sfgov.org/Public-Safety/Police-Department-Incidents-Current-Year-2018-/956q-2t7k
