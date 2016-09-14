# California deaths in custody

This data might be too small and complicated for this project. Trying to reconcile data from DOJ and Muckrock requests.




# From CA DOJ

https://openjustice.doj.ca.gov/death-in-custody/overview
https://openjustice.doj.ca.gov/data

https://openjustice.doj.ca.gov/downloads/ca_doj_deaths_in_custody_raw_2000-2015_05-14-2016.csv

https://openjustice.doj.ca.gov/downloads/ca_doj_county_deaths_in_custody_summary_2005-2014_02-17-2016.csv



# From Muckrock



## Converting

```sh
in2csv Kelly_Davis_Death_in_Custody_2013_request.xlsx --sheet '2013 Death in Custody data' --no-inference > 2013.csv

in2csv Maass_Request_PRA_2014_DIC_data.xlsx --sheet '2014 DIC Data' --no-inference > 2014.csv

```

