# Crime trends in the city of St. Louis

This project aims to understand and classify crime trends in the city of St. Louis, MO, over the past decade (beginning in 2008).  This project leverages crime data from the St. Louis metropolitan police department, hourly weather data from NOAA, and monthly housing economy data from Zillow research.

### Data sources

The <b>crime data</b> is obtained from:

http://www.slmpd.org/Crimereports.shtml

Information about this data is included in this repository, at:

https://github.com/ryanmwilson/StL_crime/blob/master/data_info/StL_PD_CrimeData_FAQ.pdf
https://github.com/ryanmwilson/StL_crime/blob/master/data_info/DOJ_handbook_crimecodes.pdf

The <b>weather data</b> is obtained from a NOAA query:

https://www.ncdc.noaa.gov/cdo-web/webservices/v2

Information about this data is included in this repository, at:

https://github.com/ryanmwilson/StL_crime/blob/master/data_info/Weather_data_readme.pdf
https://github.com/ryanmwilson/StL_crime/blob/master/data_info/Weather_data_codebook.pdf

The <b>housing data</b> is obtained from Zillow Research:

https://www.zillow.com/research/data/

Information about this data is available on the linked page.

### Directory structure 

The data are too large to include in this repository.  The raw data should be stored in a local `/raw_data` directory, with the subdirectories `stl_crime_data`, `stl_weather`, and `zillow`.
