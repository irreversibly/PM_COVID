# Exposure to air pollution and COVID-19 mortality in the United States
This is the data repository for public available code and data to reproduce analyses in "Exposure to air pollution and COVID-19 mortality in the United States".

<b>Code: </b><br>
Prepossing.R includes the code to extract all necessary data and prepocess data for statistical analyses.

Analyses.R includes the code to implement zero-inflated negative binomial mixed models in primary, secondary and sensitivity analyses.

Figure.R includes the code to generate figures in Main Text and Supplementary Materials.

<b>Data: </b><br>
county_pm25.csv: the county-level PM2.5 exposure data averaged across the period 2000-2016 and averaged across grid cells in each county. For more source information see Additional Data Source section.

temp_seasonal_county.csv: the county-level seasonal temperature and relative humidity data, summer and winter averaged across the period 2000-2016 and averaged across grid cells in each county. For more source information see Additional Data Source section.

census_county_interpolated.csv: the county-level socioeconomic and demographic variables from 2012-2016 American Community Survey (https://www.census.gov/programs-surveys/acs/data.html).

county_base_mortality.txt, county_old_mortality.txt: additional county-level socioeconomic and demographic variables from 2009-2016 
US CDC Compressed Mortality Data (https://wonder.cdc.gov/cmf-ICD10.html).

brfss_county_interpolated.csv: the county-level behavioral risk factor variables for 2011 US CDC Behavioral Risk Factor Surveillance System (https://www.cdc.gov/brfss/).

statecode.csv: A map between state name and state abbreviations.

<b>Additional Data Source: </b><br>
The county-level PM2.5 exposure data can be created via PM2.5 predictions from The Atmospheric Composition Analysis Group at Dalhouse University (http://fizz.phys.dal.ca/~atmos/martin/). Please visit the detailed instructions below

* Download PM25 predictions: https://github.com/NSAPH/data_requests/tree/master/request_projects/oct2019_download_rm_pm/ <br>
* County-level aggregation: https://github.com/NSAPH/data_requests/tree/master/request_projects/mar2020_rough_county_confounders/ <br>

We acknowedge Randall Martin and members from The Atmospheric Composition Analysis Group at Dalhouse University to provide open-source datasets.

The seasonal temperature and relative humidity data can be created via 4km × 4km temperature and relative humidity predictions from Gridmet via google earth engine (https://developers.google.com/earth-engine/datasets/catalog/IDAHO_EPSCOR_GRIDMET).

We acknowedge John Abatzoglou and members from Climatology Lab at University of Idaho to provide open-source datasets.

<b>Contact Us: </b><br>
* Email: fdominic@hsph.harvard.edu

<b>Terms of Use:</b><br>
Authors/funders retain copyright (where applicable) of code on this Github repo and the article posted on medRxiv (under review). Anyone who wishes to share, reuse, remix, or adapt this material must obtain permission from the corresponding author. By using the contents on this Github repo and the article, you agree to cite:

Wu, X., Nethery, R.C., Sabath, M.B., Braun, D. and Dominici, F., 2020. Exposure to air pollution and COVID-19 mortality in the United States. medRxiv.

This GitHub repo and its contents herein, including data, link to data source, and analysis code that are intended solely for reproducing the results in the manuscript "Exposure to air pollution and COVID-19 mortality in the United States". The analyses rely upon publicly available data from multiple sources, that are often updated without advance notice. We hereby disclaim any and all representations and warranties with respect to the site, including accuracy, fitness for use, and merchantability. By using this site, its content, information, and software you agree to assume all risks associated with your use or transfer of information and/or software. You agree to hold the authors harmless from any claims relating to the use of this site.

