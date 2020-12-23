## Data files for COMM318 _Stories from data_ Final Project


Welcome to my data folder! 

This is my data hub, containing ALL the data files utilized in creating my final story. My data folder is organized into three subfolders (raw data, cleaned data, and exported subset data). The raw data is all unedited, unaltered, raw data files pulled from three main sources linked down below. The clean data follows the raw data; for each raw data file, there exists a related clean data file which contains the relevant information, renamed columns, etc. Finally, the exported subset data contains subsetted data that was exported while analyzing the clean data files in my analysis notebooks. These subset data files are specifically incorporated in creating visualizations as well.

### Three Data Subfolders:

**Subfolder 1: raw_data** (All RAW data files)

- `06_to_19.csv` : data downloaded from World Happiness Report that contains all happiness data and relevant survey data variables from 2006 to 2019  

- subfolder: 2020 
- `covid19_cases_US.csv`: data downloaded from Novel Coronavirus Visual Dashboard that contains cases data for US only
- `covid19_cases_global.csv` : data downloaded from Novel Coronavirus Visual Dashboard that contains cases data for all other countries around the world 
- `china.csv` : happiness survey data downloaded from YouGov with happiness data in 2020 for China
- `denmark.csv` : happiness survey data downloaded from YouGov with happiness data in 2020 for Denmark
- `finland.csv` : happiness survey data downloaded from YouGov with happiness data in 2020 for Finland
- `india.csv` : happiness survey data downloaded from YouGov with happiness data in 2020 for India
- `malaysia.csv` : happiness survey data downloaded from YouGov with happiness data in 2020 for Malaysia
- `mexico.csv`: happiness survey data downloaded from YouGov with happiness data in 2020 for Mexico
- `saudi_arabia.csv`: happiness survey data downloaded from YouGov with happiness data in 2020 for Saudi Arabia
- `united_states.csv`: happiness survey data downloaded from YouGov with happiness data in 2020 for US

Sources: 
- World Happiness Report 2006-2019: Helliwell, John F., Richard Layard, Jeffrey Sachs, and Jan-Emmanuel De Neve, eds. World Happiness Report. New York: Sustainable Development Solutions Network, https://worldhappiness.report/
- Happiness Data 2020: Jones, Sarah P., Imperial College London Big Data Analytical Unit and YouGov Plc. 2020, Imperial College London YouGov Covid Data Hub, v1.0, YouGov Plc, April 2020, https://github.com/YouGov-Data/covid-19-tracker
- COVID-19 Cases Data 2020: Dong E, Du H, Gardner L. An interactive web-based dashboard to track COVID-19 in real time. Lancet Inf Dis. 20(5):533-534. doi: 10.1016/S1473-3099(20)30120-1", https://github.com/CSSEGISandData/COVID-19
 
 
**Subfolder 2: cleaned_data** (All CLEANED versions of data files from raw_data subfoler)

- `06_19_hap_cleaned.csv` : cleaned dataset version of 06_to_19.csv datafile with happiness data 2006-2019

- subfolder: 2020
- `china_covid.csv` : cleaned dataset of COVID-19 cases data for China only from covid19_cases_global.csv
- `china_hap_cleaned.csv` : cleaned dataset of happiness ratings 2020 for China from china.csv
- `denmark_covid.csv` : cleaned dataset of COVID-19 cases data for Denmark only from covid19_cases_global.csv
- `denmark_hap_cleaned.csv` : cleaned dataset of happiness ratings 2020 for Denmark from denmark.csv
- `finland_covid.csv` : cleaned dataset of COVID-19 cases data for Finland only from covid19_cases_global.csv
- `finland_hap_cleaned.csv` : cleaned dataset of happiness ratings 2020 for Finland from finland.csv
- `india_covid.csv` : cleaned dataset of COVID-19 cases data for India only from covid19_cases_global.csv
- `india_hap_cleaned.csv` : cleaned dataset of happiness ratings 2020 for India from india.csv
- `malaysia_covid.csv` : cleaned dataset of COVID-19 cases data for Malaysia only from covid19_cases_global.csv
- `malaysia_hap_cleaned.csv` : cleaned dataset of happiness ratings 2020 for Malaysia from malaysia.csv
- `mexico_covid.csv` : cleaned dataset of COVID-19 cases data for Mexico only from covid19_cases_global.csv
- `mexico_hap_cleaned.csv` : cleaned dataset of happiness ratings 2020 for Mexico from mexico.csv
- `sa_covid.csv` : cleaned dataset of COVID-19 cases data for Saudi Arabia only from covid19_cases_global.csv
- `saudi_arabia_hap_cleaned.csv` : cleaned dataset of happiness ratings 2020 for Saudi Arabia from saudi_arabia.csv
- `us_covid.csv` : cleaned dataset of COVID-19 cases data for US only from covid19_cases_global.csv
- `us_hap_cleaned.csv` : cleaned dataset of happiness ratings 2020 for US from united_states.csv

**Subfolder 3: exported_subset_data** (All subsetted datasets that were created and exported during analysis; primary sub-datasets used for creating visualizations)

- subfolder: happiness_2020 (2020 happiness related exported subsets during analysis)
- `interpolated_china.csv` : subset data from 2020 China Analysis that has interpolated rolling means for happiness data in China
- `interpolated_denmark.csv` : subset data from 2020 Denmark Analysis that has interpolated rolling means for happiness ratings in Denmark
- `interpolated_finland.csv` : subset data from 2020 Finland Analysis that has interpolated rolling means for happiness ratings in Finland
- `interpolated_india.csv` : subset data from 2020 India Analysis that has interpolated rolling means for happiness ratings in India
- `interpolated_malaysia.csv` : subset data from 2020 Malaysia Analysis that has interpolated rolling means for happiness ratings in Malaysia
- `interpolated_mexico.csv` : subset data from 2020 Mexico Analysis that has interpolated rolling means for happiness ratings in Mexico
- `interpolated_saudi_arabia.csv` : subset data from 2020 Saudi Arabia Analysis that has interpolated rolling means for happiness ratings in Saudi Arabia
- `interpolated_us.csv` : subset data from 2020 US Analysis that has interpolated rolling means for happiness ratings in US

- subfolder: covid (COVID-19 related exported subsets during analysis)
- `covid_china.csv` : subset data from 2020 China Analysis with date, # of cases, daily changes cases counts for China
- `covid_denmark.csv` : subset data from 2020 Denmark Analysis with date, # of cases, daily changes cases counts for Denmark
- `covid_finland.csv` : subset data from 2020 Finland Analysis with date, # of cases, daily changes cases counts for Finland
- `covid_india.csv` : subset data from 2020 India Analysis with date, # of cases, daily changes cases counts for India
- `covid_malaysia.csv` : subset data from 2020 Malaysia Analysis with date, # of cases, daily changes cases counts for Malaysia
- `covid_mexico.csv` : subset data from 2020 Mexico Analysis with date, # of cases, daily changes cases counts for Mexico
- `covid_saudi_arabia.csv` : subset data from 2020 Saudi Arabia Analysis with date, # of cases, daily changes cases counts for Saudi Arabia
- `covid_us.csv` : subset data from 2020 US Analysis with date, # of cases, daily changes cases counts for US

- subfolder: for_visualizations (subsets generated used to make visualizations for final story)
- `19_20_comp.csv` : subset data with 2019 happiness rating means for the 8 countries and 2020 means; used to generate paired bar graph visualization
- `geo_graph_data.csv` : final subset data of 2019 happiness rating means for all countries with available data; used to generate choropleth geomap visualization
- `hap_variables.csv` : subset data containing happiness ratings, specific variables of interest; used to generate table of 2019 happiness 
- `regional_comp_long.csv`: subset data containing happiness ratings from 2006 to 2019 for all countries and their corresponding regions as a separate column; used to generate small multiples plot with 10 regions and their happiness ratings plotted from 2006-2019
- `variables.csv`: final subset data of four variables (GDP per capita, life expectancy, delivery quality, and social support) and happiness ratings across all years; used to aggregate and groupby country and generate small multiples visualization of correlational graphs between four variables listed and happiness


