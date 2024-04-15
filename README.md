# AZURE DATA_FACTORY 
## PROJECT COVID19

###### In this project I worked with COVID 19 data from the ECDC, requesting the information through the URL https://www.ecdc.europa.eu/en/covid-19/data. The data is requested every 24 hours through Azure Data Factory using triggers, and then transformed with dataflows, pyspark and hdinsight, the data is stored in SQL. Below I leave the architecture that I used for the project.
##### Architecture
![alt text](https://github.com/dariog721/AZURE_DATA_FACTORY_COVID19/blob/main/Images/Architecture/Architecture.png)
##### Data Flows 
###### Cases and Deaths
![alt text](https://github.com/dariog721/AZURE_DATA_FACTORY_COVID19/blob/main/Images/Data%20Flow/cases_deaths.png)
###### Hospital admissions
![alt text](https://github.com/dariog721/AZURE_DATA_FACTORY_COVID19/blob/main/Images/Data%20Flow/hospital_admission.png)
##### Pipelines
###### Execute ECDC data
![alt text](https://github.com/dariog721/AZURE_DATA_FACTORY_COVID19/blob/main/Images/Pipelines/Execute/Execute_ECDC_data.png)
###### Execute population data
![alt text](https://github.com/dariog721/AZURE_DATA_FACTORY_COVID19/blob/main/Images/Pipelines/Execute/Execute_population_data.png)
##### Data 
###### Info https://www.ecdc.europa.eu/en/covid-19/data
##### Credits 
The main idea is by Ramesh Ratnasamy (https://www.linkedin.com/in/ramesh-retnasamy/)
