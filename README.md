<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Berlin Brandenburg (BER) Airport Analysis
Martynas Zigmantas & Alexander Groenert

*Data Analysis, Remote & 2024*

*This repository contains Jupiter notebooks to scrape the web (Srape Wrapper.ipynb) along with notebooks for cleaning the data: cleaning_arrivals & cleaning_departures should be ran before the Hypothesis and statistics_scripts notebook, airlines_list.csv is a filter for budget/premium. The folder "Data" is where the daily scraped data frames are saved, "Href Links" are where the .txt files with the links of flights used by the scraper are saved. "GOLDEN TABLES" are where the final 10,000 flights cleaned, transformed and concatenated are saved. "Survey CSV" contains the files of our survey responses and the final report slides are Berlin-Brandenburg-Airport-An-Analysis-Based-on-Survey-Feedback.pdf. Tableau dashboards for this project are linked at the bottom of this page.*

### This public project repository contains no final data from the days of flights scraped and the "Data" and "GOLDEN TABLES" folders are empty. One 'links' file for arrivals and departures remains in the "Href Links" folder for the purpose of demonstration.

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

<a name="organization"></a>

## Organization
Code written in Python using Jupiter notebook and Visual Studio Code. Dashboards made with Tableau.

<a name="links"></a>

## Links

[Repository](https://github.com/Blyatman-coder/berlin_airport_project)  
[Airport](https://ber.berlin-airport.de/en.html)  
[Arrival Dashboard](https://public.tableau.com/views/ArrivalsBerlin/Analysis?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  
[Departure Dashboard](https://public.tableau.com/views/DeparturesBerlin/Analysis?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  