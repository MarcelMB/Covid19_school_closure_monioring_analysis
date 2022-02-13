# Covid19 school closure monioring analysis

## Motivation

Since the beginning of 2020 Covid-19 has disrupted school education around the globe. This analysis gives an overview of the golbal extent of school closures and alternative models of partially opened schools. It also evluates the potential discrepancy in the response to covid-19 to school cosures betwen countries of different income groups (World bank classification on country income groups). 
Within the lasty years remote learning capabilities became important. This analysis also aims on investigating different media of remote learning between countries.  
The analysis includes timepoints from early 2020 till the end of 2021.


## How to use?

The analysis code is based on several jupyter notebooks.
The dataset *UNESCO_school_closures_database* is included. Check the Data source chapter for credits to its origin.


1. In a first step the dataset is cleaned and summarized?  
Use: *data_cleaning_notebook.ipynb*
At the end this step saves a cleaned csv file.

2. If needed the cleaned csv file can be loaded into the MySQL workbench
First create a new empty schema in MySQL.
Change in the jupyter notebook the "connecting string" variable to the relevant schema name that you just cerated in your My SQL workbench.
Use: *create_mysql_database.ipynb*

3. The following jupyter notebook explores the data and plots the relevant figures. Figures are saved to the current working directory. 
Use: *exploratory_analysis_and_plots*

4. An example statistical hypothesis testing using a two-sample t-test is used in a different jupyter notebook. Here the average amount of closed schools due to Covid-19 between low and high income countries is compared. Further details are mentioned in the markdown areas of the notebook. 
Use: *unesco_data_hypothesis_testing*

## Data source:

UNESCO Institute for Statistics (Excel format)
https://covid19.uis.unesco.org/global-monitoring-school-closures-covid19/


Other resources of updated and similar datasets:
https://covid19.uis.unesco.org/data/
https://en.unesco.org/covid19/educationresponse

## License
