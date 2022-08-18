# mta_recovery
Analysis of MTA's ridership change from the first four months of 2021 to the first four months of 2022

I scraped and analyzed turnstile data and metro card data from the Metropolitan Transportation Authority from the periods of Jan 01, 2021 to April 30, 2021 and Jan 01, 2022 to April 30, 2022. 

  Caveats: Subway stations were named differently in each datasets.
  
  For example, a station could be written as 42 street-Port Authority in one dataset and be written as Port Auth & 42nd St in another. There were also instances where we have a station simply listed as Broadway in one dataset and we have about six stations in the other dataset that has Broadway hyphenated with some other name. It would be difficult to simply assume that all six Broadway stations in one dataset equal to the sole Broadway in the other. In these situations, I simply skip the stations altogether. 
 Using the Lookup function in Excel as well as manually searching through, I was able to accurately confirm about 100 stations that had similar names. 
