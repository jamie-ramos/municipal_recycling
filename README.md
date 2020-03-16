The dataset is available in both an .xlxs and .csv format. There are two tables, one with the raw data and one with the z-scores of the data. Z-scores were used for normalization to indicate the distance from the arithmetic mean in standard deviations, therefore helping to identify programs that are over or under performing compared to the average (especially once the dataset expands to more municipalities). There are no duplicate variables, and all fields have been filled; no cleaning should be necessary.

Naming for the files should be as follows:

year\_datasettype

Where _year_ is the year of the data being reported, and

where _datasettype_ indicates whether it is the raw data (&quot;raw&quot;) or the normalized data (&quot;normal&quot;).

This naming convention originally contained a third value for municipalities, indicating which municipalities are included. However, due to the possibility of a future expansion of municipal scope, this was not chosen for the final naming convention. **Instead, each year should update the metadata**  **keyword**  **and**  **description**  **attributes according to any added city programs.**


**Data Dictionary**


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
| **zmetal****  ** | ZScore of Metal Tonnage | Numerical | Any number | ZScore of total tonnage of metal recycled in 2017 (from city reports), different metal types added into single value |
| **zpaper** | ZScore of Paper Tonnage | Numerical | Any number | ZScore of total tonnage of paper recycled in 2017 (from city reports), different paper types added into single value |
| **zplastic** | ZScore of Plastic Tonnage | Numerical | Any number | ZScore of total tonnage of plastic recycled in 2017 (from city reports), different plastic types added into single value |
| **zaverage\_Cost** | ZScore of Average Cost per Ton | Numerical | Any number | ZScore of averaged cost of recycling a ton of materials in USD in 2017 (from city reports) |
| **zdiversion\_Rate** | ZScore of Diversion Rate | Numerical | Any number | ZScore of total percentage of diverted landfill materials in 2017, pulled directly from report |
| **zpopulation** | ZScore of Population Size | Numerical | Any number | ZScore of population size in people (Census) |
| **zarea** | ZScore of Area | Numerical | Any number | ZScore of area of city in miles squared (Census) |
