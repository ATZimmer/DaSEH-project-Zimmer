# imported  CDC daily particulate dataset
https://data.cdc.gov/Environmental-Health-Toxicology/Daily-County-Level-PM2-5-Concentrations-2001-2019/dqwm-pbi7/about_data

created sample of data to test renaming columns - date_preview, date_reordered, test 

packages used: tidyverse, janitor.

Cleaned and reordered dates and years in County_PM_Levels

Imported county gkpg file and changed state and county ID columns from character class to numeric, to match County_PM_Levels
created new object as counties_numeric

cleaned test objects from workspace

packages used: maps, sf