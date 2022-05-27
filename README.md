# README

The purpose of this project is to see if we can predict homelessness by city from the city's budget. The hypothesis here is that something in the way that a city decides to spend its funds will give an insight to a model on how to predict number of homeless.

Result: Due to time constraints, there wasn't enough time to clean enough of the data to create a good predictive model for homelessness from city budget. However, when running just the city budget data, a DecisionTreeRegressor was able to account for the variability in test values 91% of the time. 

### Data Sources
- [FISC Database](https://www.lincolninst.edu/research-data/data-toolkits/fiscally-standardized-cities/search-database): `fisc_full_dataset_2017_update(1).xlsx`, `fisc_data.csv` derived from the Excel. The **Fiscally Standardized Cities (FiSC)** database makes it possible to compare local government finances for over 200 of the largest U.S. cities across more than 120 categories of revenues, expenditures, debt, and assets. 


- [US Data.gov Homelessness Count](https://catalog.data.gov/dataset/homelessness-count-usa): `Homelessness_Count_-_USA.csv` 

- [US 2015 AHAR: Part 1 - PIT Estimates of Homelessness in the U.S.](https://www.hudexchange.info/resource/4832/2015-ahar-part-1-pit-estimates-of-homelessness/), [PDF for AHAR 2015](https://www.huduser.gov/portal/sites/default/files/pdf/2015-AHAR-Part-1.pdf)

unused
- [US Data Homelessness](https://datahub.io/gavram/homelessness#readme): `us_data_homelessness_by_year.csv`




### Terms

- **The Continuum of Care (CoC) Homeless Assistance Program** assists individuals and families experiencing homelessness by helping homeless individuals and families move into transitional and permanent housing. 


- **Chronically Homeless Individuals** are homeless individuals with disabilities who have either been continuously homeless for a year or more or have experienced at least four episodes of homelessness in the last three years. [US Data Homelessness](https://www.hudexchange.info/resource/4832/2015-ahar-part-1-pit-estimates-of-homelessness/)

- **Individuals** are people who are not part of a family with children during their episode of homelessness. They are homeless as single adults, unaccompanied youth, or in multiple-adult or multiple-child households.[US Data Homelessness](https://www.hudexchange.info/resource/4832/2015-ahar-part-1-pit-estimates-of-homelessness/)

- **Point-in-Time Counts** are unduplicated 1-night estimates of both sheltered and unsheltered homeless populations. The 1-night counts are conducted by Continuums of Care nationwide and occur during the last week in January of each year.[US Data Homelessness](https://www.hudexchange.info/resource/4832/2015-ahar-part-1-pit-estimates-of-homelessness/)

Many other definitions can be found on Page 2 of the [2015 AHAR Report](https://www.huduser.gov/portal/sites/default/files/pdf/2015-AHAR-Part-1.pdf)