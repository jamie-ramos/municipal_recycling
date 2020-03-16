# Readme

This dataset was created for a course at the iSchool at the University of Washington in the winter of 2020. It is a breakdown of sizes, recycling rates, and diversion rates and costs for the cities of Palo Alto, San Francisco, and Seattle. The intended audience is municipal policymakers. It is freely available to the public.

The dataset is available in both an .xlxs and .csv format. There are two tables, one with the raw data and one with the z-scores of the data. Z-scores were used for normalization to indicate the distance from the arithmetic mean in standard deviations, therefore helping to identify programs that are over or under performing compared to the average (especially once the dataset expands to more municipalities). There are no duplicate variables, and all fields have been filled; no cleaning should be necessary.

## Table of Contents

- [Naming](#naming)
- [Data Dictionary](#datadictionary)
- [Metadata](#metadata)
- [Security](#security)
- [Contact](#contact)



## Naming
Naming for the files should be as follows:

          year_datasettype

  Where _year_ is the year of the data being reported, and

  where _datasettype_ indicates whether it is the raw data (&quot;raw&quot;) or the normalized data (&quot;normal&quot;).

This naming convention originally contained a third value for municipalities, indicating which municipalities are included. However, due to the possibility of a future expansion of municipal scope, this was not chosen for the final naming convention. **Instead, each year should update the metadata**  **keyword**  **and**  **description**  **attributes according to any added city programs.**


## Data Dictionary


| **Variable** | **Variable Name** | **Measurement Unit** | **Allowed Values** | **Definition** |
| --- | --- | --- | --- | --- |
| **city\_Program** | City Program | String | US city names | City name |
| **metal** | Metal Tonnage | Numerical | Integers greater than 0 | Total tonnage of metal recycled in 2017 (from city reports), different metal types added into single value |
| **paper** | Paper Tonnage | Numerical | Integers greater than 0 | Total tonnage of paper recycled in 2017 (from city reports), different paper types added into single value |
| **plastic** | Plastic Tonnage | Numerical | Integers greater than 0 | Total tonnage of plastic recycled in 2017 (from city reports), different plastic types added into single value |
| **average\_Cost** | Average Cost per Ton | Numerical | Numbers greater than 0 (USD) | Averaged cost in USD of recycling a ton of materials in 2017 (from city reports) |
| **diversion\_Rate** | Diversion Rate | Numerical | Numbers between 0-100 (percentage) | Total percentage of diverted landfill materials in 2017, pulled directly from report |
| **population** | Population Size | Numerical | Integers greater than 0 | Population size in people (Census) |
| **area** | Area | Numerical | Numbers greater than 0 (miles squared) | Area of city in miles squared (Census)  |
| **zmetal** | ZScore of Metal Tonnage | Numerical | Any number | ZScore of total tonnage of metal recycled in 2017 (from city reports), different metal types added into single value |
| **zpaper** | ZScore of Paper Tonnage | Numerical | Any number | ZScore of total tonnage of paper recycled in 2017 (from city reports), different paper types added into single value |
| **zplastic** | ZScore of Plastic Tonnage | Numerical | Any number | ZScore of total tonnage of plastic recycled in 2017 (from city reports), different plastic types added into single value |
| **zaverage\_Cost** | ZScore of Average Cost per Ton | Numerical | Any number | ZScore of averaged cost of recycling a ton of materials in USD in 2017 (from city reports) |
| **zdiversion\_Rate** | ZScore of Diversion Rate | Numerical | Any number | ZScore of total percentage of diverted landfill materials in 2017, pulled directly from report |
| **zpopulation** | ZScore of Population Size | Numerical | Any number | ZScore of population size in people (Census) |
| **zarea** | ZScore of Area | Numerical | Any number | ZScore of area of city in miles squared (Census) |

## Metadata
Schema Used: Project Open Data


| **Attribute** | **Value** |
| --- | --- |
| accessLevel | public |
| accrualPeriodicity | R/P1Y |
| fn | Jamie Ramos |
| hasEmail | [mailto:jamiemramos18@gmail.com](mailto:jamiemramos18@gmail.com) |
| describedBy | [https://github.com/jamie-ramos/municipal\_recycling](https://github.com/jamie-ramos/municipal_recycling) |
| description | This dataset is a breakdown of sizes, recycling rates, and diversion rates for the cities of Palo Alto, San Francisco, and Seattle. The intended audience is municipal policymakers. This dataset was curated for a class at the University of Washington in the winter of 2020. |
| accessURL | [https://github.com/jamie-ramos/municipal\_recycling/blob/master/2017\_raw.csv](https://github.com/jamie-ramos/municipal_recycling/blob/master/2017_raw.csv) |
| downloadURL | https://github.com/jamie-ramos/municipal\_recycling/raw/master/2017\_raw.csv |
| format | CSV |
| mediaType | CSV |
| issued | 2020-03-15 |
| keyword | &quot;recycling&quot;, &quot;diversion&quot;, &quot;palo alto&quot;, &quot;seattle&quot;, &quot;san francisco&quot;, &quot;washington&quot;, &quot;california&quot; |
| landingPage | [https://github.com/jamie-ramos/municipal\_recycling](https://github.com/jamie-ramos/municipal_recycling) |
| language | en-us |
| modified | 2020-03-15 |
| publisher | Jamie Ramos |
| references | [https://sfpublicworks.org/sites/default/files/Recology%20San%20Francisco%20Companies%27%20Annual%20Report%20for%20Rate%20Year%202017.pdf](https://sfpublicworks.org/sites/default/files/Recology%20San%20Francisco%20Companies%27%20Annual%20Report%20for%20Rate%20Year%202017.pdf),  [http://www.seattle.gov/Documents/Departments/SPU/Documents/2017RecyclingProgramReport.pdf](http://www.seattle.gov/Documents/Departments/SPU/Documents/2017RecyclingProgramReport.pdf),  [https://www.cityofpaloalto.org/civicax/filebank/documents/63577](https://www.cityofpaloalto.org/civicax/filebank/documents/63577), [https://www.seattle.gov/Documents/Departments/SPU/Documents/2017AnnualRecyclingReport06292018Final.pdf](https://www.seattle.gov/Documents/Departments/SPU/Documents/2017AnnualRecyclingReport06292018Final.pdf), [https://data.census.gov/cedsci/](https://data.census.gov/cedsci/) |
| Rights, | These data are freely available to all people, both in this repository and their respective government repositories. |
| temporal | 2020/P1Y |
| theme | recycling, diversion |
| title | Recycling Program Comparison |



## Security

These data are freely available to the public.

## Contact
Jamie Ramos
jamiemramos18@gmail.com
