# datascience_project
Project for prediction of immigrant displacement in South Sudan

Notes from project:


According to the pdf provided in this folder, describing the pulling and pushing factors of the South Sudanese Crisis, a few data sources have been placed in this folder. For further insights, or extra research you can refer to the data source at https://data.humdata.org/dataset and search for the countries of interest. We also used the same source to extract the data relevant to the South Sudan Crisis.

More documents describing the situation and for further analysis.
https://data2.unhcr.org/en/search?sv_id=5&geo_id=0&type%5B0%5D=document&sector_json=%7B%220%22%3A+%220%22%7D&sector=0&page=1 

ACLED south sudan.csv
All the conflict (both violent and non-violent) quantified per incident as collected by ACLEDdata.org in South Sudan

Refugees from South Sudan all.json
UNHCR-collected. All aggregated refugees per month since the conflict started whose origin is from South Sudan. CoO (country of origin)

Given South Sudan location, there are 5 potential countries of arrivals/movement where refugees preferred to move: Uganda, Sudan, Democratic Republic of Congo (DRC), Kenya and Ethiopia. 

Each country has a .json file, summarizing the arrivals to the country per month called “Refugees to [country].json 

Plus, there is another .json file with the preferred state/region/location inside the country of arrival (CoA). This is called “Refugees to [country] per [region/district/location].json. 

We are also adding the Kenya sex disaggregation to see patterns of movement between men and women and locations. We don’t have that file for the other countries, only Kenya. It is called refugees to Kenya per sex.json

WFP prices food.csv
Adding the prices of food, as according to the REACH report (PDF enclosed, page 3) it is also another factor for movement, in addition to conflict. 

REACH PDF report
It is a report about the factors that exacerbate refugee movement - besides conflict. In page 3, there are the results of the survey they conducted, with their main findings.  
