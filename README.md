# Covid19 school closure monioring analysis

## Motivation

Since the beginning of 2020 Covid-19 has disrupted school education around the globe. This analysis gives an overview of the golbal extent of school closures and alternative models of partially opened schools. It also evluates the potential discrepancy in the response to covid-19 to school cosures betwen countries of different income groups (World bank classification on country income groups). 
Within the lasty years remote learning capabilities became important. This analysis also aims on investigating different media of remote learning between countries.  
The analysis includes timepoints from early 2020 till the end of 2021.





## How to use?

The analysis code is based on several jupyter notebooks:


1. In a first step the dataset is cleaned and summarized?  
Use:*data_cleaning_notebook.ipynb*
At the end this step saves a cleaned csv file.

2. If needed the cleaned csv file can be loaded into the MySQL workbench
First create a new empty schema in MySQL.
Change in the jupyter notebook the "connecting string" variable to the relevant schema name that you just cerated in your My SQL workbench.
Use: *create_mysql_database.ipynb*
