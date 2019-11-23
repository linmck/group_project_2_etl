# group_project_2_etl
ETL Group Project


What data sources are you using?
Census Data - https://factfinder.census.gov/
Oregon Library Directory - https://data.oregon.gov/dataset/Oregon-Library-Directory/6x9d-idz4


What’s the end product you want to create?
Create a foundation for identifying key statistics on the neighborhoods that have a public library as a resource for their community. We will be joining key zip code level datapoints with each Oregon public library branch address. 


How will you store it?
Relational Database (Postgres)


How will you transform the data?
The data pulled from the Oregon Library Directory api will need to be cleaned (removing 4 digit delivery route portion of the zip code, removing columns that are not needed, remove all non-public libraries)
The census data exports will need to be cleaned (pull out Household Income, Poverty Level, Population values for all Oregon zip codes)
We need to join these two datasets on zip code


What additional challenges will you give yourself if you have time?
Pull in public education/public school information for the same zip codes (school ranking, graduation rate, drop out rate, number of students
