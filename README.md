# Goal
To examine world happiness scores in relation to GDP per capita.

# License
This project uses data that is governed by [Kaggle Terms and Conditions](https://www.kaggle.com/datasets/unsdsn/world-happiness/data) and [OECD Data Explorer Terms and Conditions](https://www.oecd.org/en/about/terms-conditions.html). Please review the terms to understand the usage rights and restrictions.

# Data
To reproduce the analysis done on this data, you can get the World Happiness Report on [Kaggle](https://www.kaggle.com/datasets/unsdsn/world-happiness/data) and nominal GDP values from [OECD Data Explorer](https://data-explorer.oecd.org/vis?lc=en&tm=DF_TABLE1_EXPENDITURE_HCPC&pg=0&snb=1&df[ds]=dsDisseminateFinalDMZ&df[id]=DSD_NAMAIN10@DF_TABLE1_EXPENDITURE_HCPC&df[ag]=OECD.SDD.NAD&df[vs]=&pd=,&dq=A.AUS+AUT+BEL+CAN+CHL+COL+CRI+CZE+DNK+EST+FIN+FRA+DEU+GRC+HUN+ISL+IRL+ISR+ITA+JPN+KOR+LVA+LTU+LUX+MEX+NLD+NZL+NOR+POL+PRT+SVK+SVN+ESP+SWE+CHE+TUR+GBR+USA...B1GQ_POP.......&to[TIME_PERIOD]=false&vw=tb). We then filtered the data to only include information from 2019. We then proceeded to merge the OECD Data Explorer and Kaggle Datasets. From here, we only kept four relevant columns in the DataFrame for the analysis as follows:

‘Country or region’ - countries relevant in both OECD Data Explorer and the World Happiness Report in the year 2019. 

‘Score’ - a country’s happiness score in the year 2019 from the World Happiness Report.

‘OBS_Value’ - a country’s nominal GDP value in the year 2019 from OECD Data Explorer. 

‘GDP per capita’ - a country’s individual score of GDP per capita in the year 2019 from the World Happiness Report.

# Special Considerations or Issues For This Data 
None.