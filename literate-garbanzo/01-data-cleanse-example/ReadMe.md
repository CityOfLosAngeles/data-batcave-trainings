# Identify and Remove Duplicate Records
# Utilize the Pandas library to find and remove duplicate records from a CSV file

---
These scripts identify duplicate records and create a "clean" file where duplicates are removed.

1. Navigate to 01-data-cleanse-example/duplicates_find.ipynb in cloned repository and run
    * creates a CSV file from the input file containing only the duplicate records
2. Run duplicates_remove.ipynb from same directory
    * removes the duplicate records from the input file using CSV module and Pandas

Input and output files are found in Resources

# OBJECTIVES

* Users will obtain a modern data cleansing process used within a city department
### Talking Points

* Why bother examining duplicates?
* How could this process be automated? 
* What is the importance of data cleansing?

### TO DO

* Make process more object oriented with conditional on the ```python pd.concat``` object.

### CAUTION

SFPD_CrimeIncidents_2018.csv in script was downloaded previously and is not to be taken as accurate or current. Users can download a data update prior to running scripts.
* DATA SOURCE: https://data.sfgov.org/Public-Safety/Police-Department-Incidents-Current-Year-2018-/956q-2t7k
