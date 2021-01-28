# COVID-19 Exploratory Data Analysis and Visualization

by **Jennie (Tram) Le**

- This is my personal project with no link to any organization. Though this data-driven analysis provides some insights about the COVID-19 situation around the world, my comments reflect my personal opinions. 

- My results are based on the data collect from John Hopkins University Center for Systems Science and Engineering and can served as a good reference for someone who are curious about the COVID-19 pandemic.


# Context

The outbreak of coronavirus occured in a market for illegal wildlife in Wuhan (China). On December 31, 2019, Chinese officials informed the first case of COVID-19. On January, 31, 2020, the US, the UK, South Korea, Italy, Vietnam, and many more reported their first COVID-19 cases. The economic and social disruption caused by the pandemic is devastating: 

- Tens of millions of people are at risk of falling into extreme poverty by health spending.
- More than 160 countries had mandated some form of school closures for at least 1.5 billion children and youth.
- Digital connectivity is now a necessity because of the pandemic and associated lockdowns.
- The COVID-19 recession has seen the tastest, steepest downgrades in consensus growth projections among all global recessions since 1990. [According to Worldbank]

The impact of COVID-19 can be compared with the impact og Global Financial crisis of 2007-2008 or World War II or many other crises we know only from the history books.

Around the end of January, 2021, the world exceeded 101 millions of cases and 2 millions of deaths. The cases still continue to rise in the future. 



# Data Collection

Data was acquired by downloading from Johns Hopskins University (the CSSEGI):
 - Confirmed Cases Dataset (global)
 - Deaths Dataset (global)
 


# Objective

Derive interesting data insights on Covid-19 and visualize the outbreak of Coronavirus at different level:

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
       
I hope this analysis will give you inspirations on the topic.
 

# Pipeline

 - Download the dataset
 - Clean and consolidate the data
 - Perform exploratory analysis (EDA)
 - Transform data into different types of dataframe and engineer new features for further study and visualizations



# Feature Engineering

For the purpose of the data, there are new variables were created:
- New cases
- New Deaths
- 7 days rolling average of new cases and new deaths
- Month, Day, Month-Year 



# Insights

- Top 10 worst affected countries are United States, India, Brazil, Russia, United Kingdom, France, Spain, Italy, Turkey, Germany.


- The global fatality rate for COVID-19 Pandemic is 2.15% by the end of January 2021.


- In the world, Yemen came in the first place with the highest fatality rate (29%) with 612 deaths and 2115 cases. Though MS Zaandam has the second highest fatality rate of 22% but this country has significant small numbers of confirmed cases (9) and  deaths(2). 



- The **United States** accounted for the world's **highest number of cases and deaths** at over 25.6M and 425K as of January 26th, 2020, according to CSSE data. Despite the highest number of deaths, the mortality rate in the US is only 1.67%. **Indian** came in **second place** with 10M infections and 153K deaths.


- In the list of the worst affected countries, **Brazil** came in third with more than 8M confirmed cases. **Russia, United Kingdom and France** came in as the third, fourth, and fifth place with relatively similar numbers of infections, over 3M. **Spain, Italy, Turkey, and Germany**  came in as the last four places in top 10 most infected countries.


- In the list of the most deathly countries, Mexico came in fourth yet the fatality rate, reached 8.5%, of the countries ranked third in the world.


- In the list of the worst infected countries, Italy had the highest fatality rate of 3.48%.


- After 100 infections were confirmed, South Korea, Vietnam, and China quickly flattened the curve while the number of infections in US, Brazil, Russia, Spain, United Kingdom, India, and Germany had a hard time controlling the infections: In less than 50 days after the first 100 cases, all countries had their infections double every day and every 3 day. After 100 days since the first 100 cases, the U.S., Brazil, and India had their cases double every 2 weeks. Vietnam is the only country had their cases double every 2 months after 300 days.


- From November 2020 to 2021, the daily new infections in the U.S. were almost half the total new infections all over the world.

- The U.S. saw a significant spike in new infections and deaths around the end of 2020 (Dec) and the start of 2021 (Jan).


- Vietnam population (96.46M) is approximately one-third of US population (328M), however, the daily new cases in US is 10,000 times higher than the daily new cases in Vietnam. Hence, Vietnam has successfully control of the pandemic in comparison with the U.S.


- Season can play a significant role in the increase of cases as the flu season can cause a second wave. The daily new cases in US reached around 100,000 to 300,000 cases during Winter (November, December, and January). The numbers of daily new cases in Spring, Summer and Fall were mostly less than 100,000.


- The number of daily new cases in Vietnam is mostly less than 20. In the summer of 2020, the number of new cases spiked up to 50 case. This happened because students who studied aboard in European or United States (hot spots of the pandemic) came back to Vietnam or foreigners travelled to Vietnam to avoid the pandemic in their countries. 


________________________________________________________________
