## My final project for COMM318 _Stories from Data_ (Fall2020)

### **Let's Look at Happiness!** - Robin Hu

Happiness -- a strange concept really. I have always heard people say.."don't worry, be happy". But what makes me happy? What makes you happy? What even is happiness?

The goal of this story is to explore happiness measures from different persectives. It can be divided into four main sections. 
- **Part I**: The first part is to look at happiness ratings in 2019. How happy were we in the most recent ~normal~ year, that is before a global pandemic took over?
- **Part II**: The second part is to look at happiness temporally and geographically. Were we happier in the past? How does the average life satisfaction and happiness scores in the US compare to that of other countries? How has happiness changed leading up to 2019?
- **Part III**: The third part dives deeper into some underlying factors that may relate to differences in happiness ratings. What factors may be underlying these differences? Given differences in happiness ratings between countries, what might the relationships be between happiness and other measures, such as GDP, health expectancies, etc. and whether one could predict the other. 
- **Part IV**: The fourth part, of course, it seems only fitting with the COVID-19 pandemic to look at happiness in 2020, in the present. Are there any correlations between COVID-19 case surges and happiness fluctuations throughout the year? How have happiness ratings changed, if at all, between 2019 and 2020 in different countries and what are some characteristics of those countries that could potentially relate to these rating changes? 

These are some of the questions I investigate in this project. This project takes an abstract concept like "happiness", operationalizes and standardizes it, and teases out some differences, relationships, and changes that are reflected within the data available on happiness. I hope this project influences you to think about happiness and maybe even expand your perceptions on the nature of happiness from a longitudinal and regional standpoint, and in relation to a massive pandemic like COVID-19.

There are three major data sources for this project. The first comes from [The World Happiness Report from the Sustainable Development Solutions Network](https://worldhappiness.report/), which extracts and compiles standardized data from the Gallup World Poll into an annual report on various measures of happiness based on self-reported values. This provides data from 2006 to 2019 which forms the crux of the story. After I completed my analysis there, it really piqued my curiosity as to how happiness could be affected in 2020. Since the World Happiness Report has yet to publish that data, I had to look elsewhere. Happiness data in 2020 comes from a research partnership between [YouGov and the Institute of Global Health Innovation (IGHI) at Imperial College London](https://github.com/YouGov-Data/covid-19-tracker) that has surveyed global opinions. These surveys luckily included the exact same Cantril ladder measure question from the Gallup World Poll. The biggest change in 2020 that I thought would influence happiness ratings was the global pandemic, of course. That is what led me to finding COVID-19 cases data from the [Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE)](https://github.com/CSSEGISandData/COVID-19) which aggregated data sources from the World Health Organization (WHO), European CDC, US CDC, US COVID Tracking Project, LA Times, and all state and local health departments.

A skeleton of this entire project is as follows:
- First there is the data folder, containing raw data, cleaned data, and all exported subset data used.
- Next, there is the data_analysis folder, that dives into investigating all the data sources from the data folder.
- Finally, there is the data_story_presentation folder which contains the final data story!

With all that being said, let's take a look at happiness!


Sources:
- Dong E, Du H, Gardner L. An interactive web-based dashboard to track COVID-19 in real time. Lancet Inf Dis. 20(5):533-534. doi: 10.1016/S1473-3099(20)30120-1", https://github.com/CSSEGISandData/COVID-19
- Helliwell, John F., Richard Layard, Jeffrey Sachs, and Jan-Emmanuel De Neve, eds. World Happiness Report. New York: Sustainable Development Solutions Network, https://worldhappiness.report/
- Jones, Sarah P., Imperial College London Big Data Analytical Unit and YouGov Plc. 2020, Imperial College London YouGov Covid Data Hub, v1.0, YouGov Plc, April 2020, https://github.com/YouGov-Data/covid-19-tracker