<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Berlin Brandenburg (BER) Airport Analysis
Alexander Groenert & Martynas Zigmantas

*Data Analysis, Remote & 2024*

*This repository contains Jupiter notebooks to scrape the web (Srape Wrapper.ipynb) along with a backup notebook. Notebooks for cleaning the data: cleaning_arrivals & cleaning_departures should be ran before the Hypothesis and statistics_scripts notebook, airlines_list.csv is a filter for budget/premium. The folder "Data" is where the daily scraped data frames are saved, "Href Links" are where the .txt files with the links of flights used by the scraper are saved. "GOLDEN TABLES" are where the final 10,000 flights cleaned, transformed and concatenated are saved. "Survey CSV" contains the files of our survey responses and the folder "Images" has screenshots of some visuals used in the slides.*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-/-questions)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description
Collecting full flight information for arrivals and departures in Berlin Brandenburg (BER) Airport through web scraping and collecting sentiment data through a survey.
Analysing the performance of different airlines, testing hypothesis and creating a useful tool to check for direct flights to/from worldwide airports and available airlines.

<a name="hypotheses-/-questions"></a>

## Hypotheses / Questions
Are premium airlines more punctual than budget airlines? Our survey shows the sentiment is that premium airlines tend to be more punctual. Our hypothesis is that premium is not more punctual than budget.

<a name="dataset"></a>

## Dataset
Our dataset was collected through web scraping 10,000 flights from the official Berlin Brandenburg (BER) Airport website: https://ber.berlin-airport.de/en.html 

<a name="workflow"></a>

## Workflow
We began to write the code that scraped the website for departures and arrivals. We then cleaned the data and added extra necessary data such as time difference columns and airline type (budget or premium). We conducted mathematical hypothesis testing, statistics and then created visual and interactive dashboards

We also had an EDA file. However, as we didn't focus on aspects that didn't have correlation, we are not including this file in an attempt to keep the scope clear for the end user. As an example: we collected wind and weather data to analyze their potential impact on our operations. However, we encountered challenges in determining whether these metrics should be applied at takeoff, landing, or other phases of operation. Despite these considerations, our analysis revealed no significant correlation between the weather data and the rest of our dataset. As a result, our exploratory data analysis (EDA) files are not included in this repository.

## Key Conclusions

After consulting with commercial airline pilots, we found that delays are often attributed to late departures, which typically lead to late arrivals (although late arrivals without late departures are possible, the are rare and mainly happen due to severe weather anomolies). We conducted separate statistical analyses of departures and arrivals from Berlin Airport and identified two main factors affecting delay likelihood: the time of day and the classification of airlines as budget or premium. Our findings indicate that flights later in the day are more prone to delays, with Berlin Airport's closure at 23:30 due to noise pollution marking any arrivals past this time as delayed. Surprisingly, budget airlines demonstrated greater punctuality compared to premium airlines, with premium airlines being 10% more likely to experience delays. These conclusions are supported by a robust dataset of over 10,000 flights and statistically significant p-values.

<a name="organization"></a>

## Organization
Code written in Python using Jupiter notebook and Visual Studio Code. Dashboards made with Tableau.

<a name="links"></a>

## Links

[Repository](https://github.com/Blyatman-coder/berlin_airport_analysis.git)  
[Slides](https://gamma.app/docs/Berlin-Brandenburg-Airport-A-Comprehensive-Analysis-0tilr74plb95g55)  
[Airport](https://ber.berlin-airport.de/en.html)  
[Arrival Dashboard](https://public.tableau.com/views/ArrivalsBerlin/Analysis?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  
[Departure Dashboard](https://public.tableau.com/views/DeparturesBerlin/Analysis?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  