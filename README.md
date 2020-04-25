# Fetch-Covid19-Data
Fetch covid19 data from worldometers.

# About Output
Script create 1 csv file and 1 data folder.
1. csv file - List of countries and its url.
2. data folder - Contain csv file for each country.
                 Each csv has file date, daily cases, total cases, daily deaths, total deaths, active cases.
                 Note- For some countries, some fields are not availabe.
                 
# Steps to run script
1. Create a folder name with name 'data'.
2. Run only get_country_list() to generate country list and its link.
   Note- run only for one time.
3. Comment get_country_list() function.
4. Run restof the code.

