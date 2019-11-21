# Colorado Election Shapefile
This shapefile comes from Todd Bleess of the Colorado State Demographer's Office and was cleaned and processed by members of Beth Malmskog's team at Colorado College. This effort was led by Haley Colgate and included Austin Eide, Matt Cooney, Edgar Santos Vega, Kadin Mangalik, and Jose Monge Castro. Some additional processing was done by MGGG staff.

## Sources
The 2018 Colorado precinct shapefile was made available to us by Todd Bleess of the Colorado State Demographer's Office. Election data come from the [Colorado Secretary of State's Office](https://www.sos.state.co.us/pubs/elections/Results/Archives.html). 2010 Decennial Census demographic data were downloaded from the [Census API](https://api.census.gov/data/2010/dec/sf1). The 2010 census block shapefile for Minnesota was downloaded from the US Census Bureau’s [TIGER/Line Shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html).

## Processing
Precincts for certain counties were not included in the shapefile provided by the Demographer's Office and were digitized from maps provided by the county. Those counties are: Boulder, Denver, Douglas, and El Paso. For Las Animas county, the voter file was geocoded and used to identify precinct boundaries. Demographic data were aggregated from the census block level and precincts were assigned to districts using [MGGG's proration software](https://github.com/mggg/maup).

## Metadata
* `COUNTYFP`: County FIPS Code
* `VTDST`: Precinct code
* `NAME`: Precinct name
* `CD116FP`: Congressional district ID
* `SLDUST`: State Senate district ID
* `SLDLST`: State House district ID
* `AG18D`: Number of votes for 2018 Democratic attorney general candidate
* `AG18R`: Number of votes for 2018 Republican attorney general candidate
* `SOS18D`: Number of votes for 2018 Democratic secretary of state candidate
* `SOS18R`: Number of votes for 2018 Republican secretary of state candidate
* `TRE18D`: Number of votes for 2018 Democratic treasurer candidate
* `TRE18R`: Number of votes for 2018 Republican treasurer candidate
* `GOV18D`: Number of votes for 2018 Democratic gubernatorial candidate
* `GOV18R`: Number of votes for 2018 Republican gubernatorial candidate
* `REG18D`: Number of registered Democratic voters for 2018 general election
* `REG18R`: Number of registered Republican voters for 2018 general election
* `USH18D`: Number of votes for 2018 Democratic US house candidates
* `USH18R`: Number of votes for 2018 Republican US house candidates
* `TOTPOP`: Total population 
* `NH_WHITE`: White, non-hispanic, population
* `NH_BLACK`: Black, non-hispanic, population
* `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population
* `NH_ASIAN`: Asian, non-hispanic, population
* `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population
* `NH_OTHER`: Other race, non-hispanic, population
* `NH_2MORE`: Two or more races, non-hispanic, population
* `HISP`: Hispanic population
* `H_WHITE`: White, hispanic, population
* `H_BLACK`: Black, hispanic, population
* `H_AMIN`: American Indian and Alaska Native, hispanic, population
* `H_ASIAN`: Asian, hispanic, population
* `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population
* `H_OTHER`: Other race, hispanic, population
* `H_2MORE`: Two or more races, hispanic, population
* `VAP`: Total voting age population
* `HVAP`: Hispanic voting age population
* `WVAP`: White, non-hispanic, voting age population
* `BVAP`: Black, non-hispanic, voting age population
* `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population
* `ASIANVAP`: Asian, non-hispanic, voting age population
* `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population
* `OTHERVAP`: Other race, non-hispanic, voting age population
* `2MOREVAP`: Two or more races, non-hispanic, voting age population

## Projection
This shapefile uses a NAD83/UTM zone 13N projection (EPSG: 2957).

## Rating
We give this shapefile an A rating. All data was obtained from the state government and was processed by MGGG collaborators. It was audited by MGGG staff.
