## Data analysis notebooks for COMM318 _Stories from data_ Final Project

Welcome to my data analysis folder!

There are three types of data analysis notebooks in this folder:
1) Exploration notebooks (titled "'' Exploration"): in these exploration notebooks, I import the raw data file, do some initial exploration, cleaning, and then export to a cleaned file. Some observations are interlaced within the code, but the headings narrate what I am doing at the key steps.
2) Analysis notebooks (titled "'' Analysis"): in these analysis notebooks, I import the cleaned data file versions, conduct analysis on available data and make observations throughout.  This is the crux of my analysis! I include concise observations that extract the key points that jumped out to me while I was conducting the analysis.
3) Visualization notebook (contains "Visualizations" in title): these notebooks contain attempts to generate potential visualizations for the final data story based on observations from analysis notebooks. Note: there are not observations in the visualization notebook since the purpose of these was to generate drafts for the things to include in my data story.

**Notebooks list:**

Pre-2020 Data Analysis:
   - `2019_Analysis`: This notebook contains preliminary analysis of 2019 happiness data only, just to get an idea of what kind of data I was working with. In this notebook, I identified a few variables that could correlate with happiness differences between countries and noted potential directions for my final data story and next steps in my analysis. This was the first very analysis notebook!
   - `2006_to_2019_Exploration`: This notebook was cleaning and taking an initial look at the 06_to_19 raw dataset for 2006 to 2019 happiness ratings. Exported clean datafile.
   - `2006_to_2019_Analysis`: This notebook contains analysis of 2006-2019 happiness data. It includes a 2019 happiness rating summary (countries ranking highest and lowest), longitudinal and regional analysis of happiness ratings, and conducting four variables correlational analysis (life expectancy, GDP per capita, social support rating, and gvt. delivery quality) followed by a multiple regression analysis.
   
2020 Data Analysis:

All subsequent notebooks are analyzing COVID-19 cases data and happiness data in 2020 for eight different countries. Start with Denmark, Finland, US, and India, but the order of the last four countries is not particularly important.
   - `2020_Denmark_Exploration`: This notebook was cleaning and taking an initial look at Denmark raw data for happiness ratings and COVID-19 cases in 2020. Exported two clean datafiles.
   - `2020_Denmark_Analysis`: This analysis notebook investigates the 2020 happiness and COVID-19 cases data for Denmark. I generated various plots generated for monthly happiness means vs. monthly cases; weekly happiness means vs. weekly cases; daily means vs. daily cases; and rolling interpolated means vs. weekly cases, concluding with a 2020 overall happiness mean. I started with Denmark since quite high on the Cantril ladder.
   - `2020_Finland_Exploration`: This notebook was cleaning and taking an initial look at datasets for COVID-19 data for Finland and happiness ratings in 2020. Exported clean datafile. 
   - `2020_Finland_Analysis`: This analysis notebook looks at 2020 happiness and COVID-19 cases data for Finland. Attempted to plot monthly happiness means vs. monthly cases; weekly happiness means vs. weekly cases; daily means vs. daily cases; interpolated means vs. weekly cases. I also calculated the happiness rating mean for all of 2020 in Finland. I conducted Finland analysis after Denmark since they are both categorized under the same region and wanted to see if there were any similarities between COVID-19 cases and happiness trends between 2019 and 2020.
   - `2020_US_Exploration`: This notebook was cleaning and initial look at datasets (COVID-19 data for US and happiness ratings).
   - `2020_US_Analysis`: This analysis notebook looks at 2020 happiness and COVID-19 cases data for US. Includes plots of monthly happiness means vs. monthly cases; weekly happiness means vs. weekly cases; daily means vs. daily cases; and rolling interpolated means vs. weekly cases. Calculated 2020 happiness mean for US. 
   - `2020_India_Exploration`: This notebook was cleaning and preliminary initial look at datasets for COVID-19 data for India and happiness ratings in 2020. Exported clean datafile.
   - `2020_India_Analysis`: This analysis notebook looks at 2020 happiness and COVID-19 cases data for India. Includes plots of monthly happiness means vs. monthly cases; weekly happiness means vs. weekly cases; daily means vs. daily cases; and rolling interpolated means vs. weekly cases. I decided to conduct analysis on India next since India ranks in the bottom 10 countries every year for happiness, so I wanted to see what differences might be there.
   - `2020_China_Exploration`: This notebook was cleaning and taking an initial look at datasets for COVID-19 data for China and happiness ratings in 2020. Exported clean data file.
   - `2020_China_Analysis`: This analysis notebook looks at 2020 happiness and COVID-19 cases data for China. Includes plots of monthly happiness means vs. monthly cases; weekly happiness means vs. weekly cases; daily means vs. daily cases; and rolling interpolated means vs. weekly cases. 
   - `2020_Mexico_Exploration`: This notebook was cleaning and looking at datasets for COVID-19 data for Mexico and happiness ratings in 2020. Exported clean data file.
   - `2020_Mexico_Analysis`: This analysis notebook investigates 2020 happiness and COVID-19 cases data for Mexico. Includes plots of monthly happiness means vs. monthly cases; weekly happiness means vs. weekly cases; daily means vs. daily cases; and rolling interpolated means vs. weekly cases. 
   - `2020_Saudi_Arabia_Exploration`: This notebook was cleaning and looking at datasets for COVID-19 data for Saudi Arabia and happiness ratings in 2020.
   - `2020_Saudi_Arabia_Analysis`: This analysis notebook looks at 2020 happiness and COVID-19 cases data for Saudi Arabia. Includes plots of monthly happiness means vs. monthly cases; weekly happiness means vs. weekly cases; daily means vs. daily cases; and rolling interpolated means vs. weekly cases.
   - `2020_Malaysia_Exploration`: This noteboook was cleaning and looking at datasets for COVID-19 data for Malaysia and happiness in 2020.
   - `2020_Malaysia_Analysis`: This analysis notebook specifically looks at 2020 happiness and COVID-19 cases data for Malaysia. Plots of monthly happiness means vs. monthly cases; weekly happiness means vs. weekly cases; daily means vs. daily cases; and rolling interpolated means vs. weekly cases.
   
Visualizations:
   - `Visualizations_Draft`: This notebook contains a compilation of generating all potential visualizations to be included in final data story. This notebook is primarily to clarify which key pieces of information I want to be presented in the visualizations.
   - `Visualizations_Happiness_Cases`: This notebook contains ONLY the code used to generate visualization for happiness cases vs. COVID-19 cases data for eight countries selected in form of small multiples figure. Purpose of this notebook is that I will run this notebook in final data story to minimize the huge block of code interrupting the flow of the story.

   