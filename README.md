# COVID-19-Visualization

# Introduction
The rapid spread in the novel corona-virus across countries, John Hopskin University have published latest data on the impact of COVID-19 over the past year. I have been going through many sources and articles to understand the fatality trend and was excited to apply data visualization on this pandemic as personal project. For visualization, I am using seaborn, pygal, plotly, and matplotlib tool available in Python.
The dataset was published by Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE) and collected from their Github page.

# Objective
Derive interesting data insights on Covid-19 and visualize the outbreak of Coronavirus at different level:<br><br>
  1. Global 
  2. Country 
  3. Geographical Map
  4. Top 10 Country
  5. Fatality Rate
  6. Worldwide Detail Report Since the Early Stage of Pandemic Till Now
  7. Timeline Analysis:
      - Global Level
      - US vs. The Rest of The World
      - Vietnam
      - Compare the situation between US & Vietnam
# Pipeline
- Load Data
- Consolidate Data
- Clean Data
- Engineer New Feature
- Exploratory Analysis with Visualization

# Feature Engineering:
For the purpose of the data, there are new variables were created:

- New cases
- New Deaths
- 7 days rolling average of new cases and new deaths
- Month, Day, Month-Year

#Insights
- Top 10 Country with the highest cases are 'USA', 'India', 'Brazil', 'Russia', 'United Kingdom', 'France', 'Spain', 'Italy', 'Turkey', 'Germany'.<br>
- The global fatality rate for COVID-19 Pandemic is 2.15%.<br>
- Yemen has the highest fatality rate (29%) with 612 deaths and 2115 cases. Though MS Zaandam has the second highest fatality rate of 22% but this country has significant small numbers of confirmed cases (9) and deaths(2).<br>
- United States is the countries with the highest confirmed cases and highest deaths. From November 2020 to 2021, the number of new cases in the U.S. was almost half the total number of new cases all over the world. The total number of deaths in the U.S. was approximately one-fourth that number of the rest of the world.<br>
- From May to November 2020, US had a low and constant number of deaths but that number was significantly increase in December 2020 and January 2021.<br>
- There was a spike in new cases for the rest of the world as of the end of December 2020 and the start of January 2021 while the number of new cases in the U.S. was quite stable during that time.<br>
- Vietnam barely has any case on a daily basis. USA has daily reported new cases mostly in the range of less than 100,000. At some time, the daily new cases can reach 200,000. The population in the US is 328M while the population in Vietnam is 96.46M. The Vietnam population is approximately one-third of the US population, however, the daily new cases in US is 10,000 times higher than the daily new cases in Vietnam. Hence, Vietnam has a great control over the pandemic while the US seems to be losing control.<br>
- Season can play a significant role in the increase of cases as the flu season can cause a second wave. The dailt new cases in US can reached mostly around 100,000 to 300,000 cases during Winter (roughly Nov, Dec, and Jan). The number of daily new cases in Spring, Summer and Fall were mostly less than 100,000.<br>
- The number of daily new cases in Vietnam is mostly less than 20. In the summer of 2020, the number of new cases can spike up to 50 case. This happened because students who studied aboard in European or United States (hot spots of the pandemic) came back to Vietnam or foreigner wanted to avoid the pandemic in Vietnam.<br>
