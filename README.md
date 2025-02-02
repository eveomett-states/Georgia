# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# Georgia Election Shapefile

This shapefile was processed by Professor Ellen Veomett and her student Arbie Hsu.

# **Sources**

The following obtained from [Redistricting Data Hub](https://redistrictingdatahub.org/) on June 19, 2024:

[Population data](https://redistrictingdatahub.org/dataset/georgia-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2023-georgia-congressional-districts-plan/) as passed Dec 7, 2023

[State House District data](https://redistrictingdatahub.org/dataset/2023-georgia-state-house-of-representatives-districts-plan/) as passed Dec 5, 2023

[State Senate District data](https://redistrictingdatahub.org/dataset/2023-georgia-state-senate-plan/) as passed Dec 5, 2023

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-georgia-precinct-boundaries-and-election-results-shapefile/) (currently not working) VEST 2020 Georgia precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-georgia-precinct-and-election-results/) VEST 2018 Georgia precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-georgia-precinct-and-election-results/) VEST 2016 Georgia precinct and election results

# **Processing**

Demographic data were aggregated from the census block level and precincts were assigned to districts using [MGGG's proration software](https://github.com/mggg/maup). Election data were also prorated onto VTDs from the original precinct shapefile using the `maup` package.

# **Metadata**

Below is a brief description of each of the listed variables in the attribute table of the VTD shapefile:

- `DISTRICT16`: County FIPS code and precinct identifier
- `CTYSOSID16`: County SOS ID based on precinct of 2016
- `PRECINCT_I16`: Precinct identifier based on precinct of 2016
- `PRECINCT_N16`: Precinct name based on precinct of 2016
- `CTYNAME16`: County name based on precinct of 2016
- `CTYNUMBER16`: State and County number based on precinct of 2016
- `CTYNUMBER216`: County number based on precinct of 2016
- `FIPS216`: County FIPS code based on precinct of 2016
- `CD`: Congressional district ID in 2021 enacted congressional map
- `SEND`: State Senate district for 2021 State Senate Adopted Plan
- `HDIST`: State House district for 2021 State House of Representatives Districts Plan
- `TOTPOP`: Total population in 2020 Census
- `NH_WHITE`: White, non-hispanic, population in 2020 Census
- `NH_BLACK`: Black, non-hispanic, population in 2020 Census
- `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population in 2020 Census
- `NH_ASIAN`: Asian, non-hispanic, population in 2020 Census
- `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population in 2020 Census
- `NH_OTHER`: Other race, non-hispanic, population in 2020 Census
- `NH_2MORE`: Two or more races, non-hispanic, population in 2020 Census
- `HISP`: Hispanic population in 2020 Census
- `H_WHITE`: White, hispanic, population in 2020 Census
- `H_BLACK`: Black, hispanic, population in 2020 Census
- `H_AMIN`: American Indian and Alaska Native, hispanic, population in 2020 Census
- `H_ASIAN`: Asian, hispanic, population in 2020 Census
- `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population in 2020 Census
- `H_OTHER`: Other race, hispanic, population in 2020 Census
- `H_2MORE`: Two or more races, hispanic, population in 2020 Census
- `VAP`: Total voting age population in 2020 Census
- `HVAP`: Hispanic voting age population in 2020 Census
- `WVAP`: White, non-hispanic, voting age population in 2020 Census
- `BVAP`: Black, non-hispanic, voting age population in 2020 Census
- `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population in 2020 Census
- `ASIANVAP`: Asian, non-hispanic, voting age population in 2020 Census
- `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population in 2020 Census
- `OTHERVAP`: Other race, non-hispanic, voting age population in 2020 Census
- `2MOREVAP`: Two or more races, non-hispanic, voting age population in 2020 Census
- `AGR18D`:  Number of votes for 2018 Democratic Commissioner of Agriculture
- `AGR18R`:  Number of votes for 2018 Republican Commissioner of Agriculture
- `ATG18D`: Number of votes for 2018 Democratic attorney general candidate
- `ATG18R`: Number of votes for 2018 Republican attorney general candidate
- `GOV18D`: Number of votes for 2018 Democratic gubernatorial candidate
- `GOV18R`: Number of votes for 2018 Republican gubernatorial candidate
- `GOV18O`: Number of votes for 2018 other party's gubernatorial candidate
- `INS18D`: Number of votes for 2018 Democratic Commissioner of Insurance
- `INS18O`: Number of votes for 2018 other party's Commissioner of Insurance
- `INS18R`: Number of votes for 2018 Republican Commissioner of Insurance
- `LAB18D`: Number of votes for 2018 Democratic Commissioner of Labor
- `LAB18R`: Number of votes for 2018 Republican Commissioner of Labor
- `LTG18D`: Number of votes for 2018 Democratic Lieutenant Governor
- `LTG18R`: Number of votes for 2018 Republican Lieutenant Governor
- `PRE16D`: Number of votes for 2016 Democratic President
- `PRE16O`: Number of votes for 2016 other party's  President
- `PRE16R`: Number of votes for 2016 Republican President
- `PSC16O`: Number of votes for 2016 other party's Public Service Commissioner
- `PSC16R`: Number of votes for 2016 Republican Public Service Commissioner
- `PSC18D`: Number of votes for 2018 Democratic Public Service Commissioner
- `PSC18O`: Number of votes for 2018 other party's Public Service Commissioner
- `PSC18R`: Number of votes for 2018 Republican Public Service Commissioner
- `SOS18D`: Number of votes for 2018 Democratic Secretary of State
- `SOS18R`: Number of votes for 2018 Republican Secretary of State
- `SOS18O`: Number of votes for 2018 other party's Secretary of State
- `SPI18D`: Number of votes for 2018 Democratic Superintendent of Public Instruction
- `SPI18R`: Number of votes for 2018 Republican Superintendent of Public Instruction
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate
- `USS20O`: Number of votes for 2020 other party's senate candidate

# **Projection**

The shapefile uses a UTM NAD83 projection (EPSG: 4269).
