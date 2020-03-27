# Oregon County Libraries as a Community Resource

## Overview

### What data sources are you using

* Census Data - https://factfinder.census.gov/ (API)
* Oregon Library Directory - https://data.oregon.gov/dataset/Oregon-Library-Directory/6x9d-idz4 (CSV)

### What’s the end product you want to create

* Create a foundation for identifying key statistics on the counties that have a public library as a resource for their community. We will be joining key county level datapoints with each Oregon public library branch.

### How will you store it

* SQLite Database

### How will you transform the data

* The data pulled will need to be cleaned (removing columns that are not needed, remove all non-public libraries, etc.)
* All data will need to be merged based on county

### What additional challenges will you give yourself if you have time

* Pull in public education/public school information for the same zip codes (school ranking, graduation rate, drop out rate, number of students
