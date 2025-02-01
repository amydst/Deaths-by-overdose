# Deaths by Drug Overdose and Potential Contributing Factors

Project Title: Deaths by Drug Overdose and Potential Contributing Factors

Team Members: Morgan Bee, Rowan Clark, Amy Dos Santos, Brian Hester, Kiley Karecki

Description/Outline: Relationship between High school graduation rates, Unemployment Rates, and Median Household Income on the Yearly rate of death by drug overdose by State for the years (2021, 2022 and 2023)

We are interested in identifying possible contributing factors to death rates by drug overdose to better understand this phenomenon and hopefully better guide efforts to reduce this rate.

- Education Rate and Drug Overdose Rate:
    The Confidence Level for each of the hypotheses below is 0.05. 
    
    Null Hypthesis:
    For adults 18 and older in the United States from the years 2021-2023, as average Education Rate increases, average Drug Overdose Rate does not change.
    Alternative Hypothesis:
    For adults 18 and older in the United States from the years 2021-2023, as average Education Rate increases, average Drug Overdose Rate decreases significantly.

    Median Household Income and Drug Overdose Rate:
    Null Hypothesis:
    For adults 18 and older in the United States from the years 2021-2023, as average Median Household Income increases, average Drug Overdose Rate does not change.
    Alternative Hypothesis:
    For adults 18 and older in the United States from the years 2021-2023, as average Median Household Income increases, average Drug Overdose Rate decreases significantly.

    Unemployment Rate and Drug Overdose Rate:
    Null Hypothesis:
    For adults 18 and older in the United States from the years 2021-2023, as average Unemployment Rate increases, average Drug Overdose Rate does not change.
    Alternative Hypothesis:
    For adults 18 and older in the United States from the years 2021-2023, as average Unemployment Rate increases, average Drug Overdose Rate also increases significantly.

Variables (averages over 2021-2023):
    * Deaths by drug overdose = Average death rate by drug overdose by total population
    * Education rate = Average Highschool graduation rates adult 18 and over (includes equivalent) by total population
    * Unemployment = Average unemployment rate by total employable population
    * Socioeconomic status = Average household median income per year


Research Questions to Answer:
    Q1.  How does education rates (high school graduation) affect overdose rates by county across different regional areas in the United States?
    Q2. Is there a link between socioeconomic status (household median income) and rate of overdoses? Does a combination of low socioeconomic status and low education rate compound the risk of drug overdose, and vice versa? 
    Q3. Does unemployment rate affect rates of drug overdose by state?

Resources used: 

    * Deaths by Drug Overdose by State:
https://data.cdc.gov/NCHS/VSRR-Provisional-Drug-Overdose-Death-Counts/xkb8-kh2a/data_preview 

    * Geographic centers of 50 US States (from GitHub user claraj)
 https://gist.github.com/claraj/3880cd48b3d8cb3a7f900aeb30b18fdd

    * High School Graduation Rate by States:
 https://data.census.gov/table?q=graduation%20rates%20by%20state 

    * Household Meadian Income by State: 
 https://data.census.gov/table/ACSST1Y2023.S1901?q=socioeconomic%20status%20by%20state 

- Conclusion: 
    We set out with a goal to analyze the relationship between drug overdose rates and potential contributing factors; High School Graduation Rates, Median Household Income, and Unemployment Rates in the US from 2021-2023. Through exploring, cleaning, and analyzing the data, our overarching goal was to determine if any of these variables mentioned above had any statistical significance to overdose rates and whether we could use them as predictors for overdose trends in the US. 
    
    The examination of High School graduation rates showed a weak negative correlation as between graduation rates and overdose rates. Our null hypothesis for the contributing factor of High School Graduation Rates was that there would be no change in drug overdose rate with a fluctuation in high school graduation rate, and an alternative hypothesis that as high school graduation rates increased, drug overdose rates would decline significantly. However, with a p-value of .412, we must fail to reject the null hypothesis. There is not sufficient evidence to suggest that a decrease in drug overdose rate with an increase of high school graduation rate did not happen by chance. The r-squared value of this regression is -.117, which is quite low. This demonstrates that the two variables are weakly correlated, and that assessing high school graduation rates will not be a sufficient indicator of any given state’s drug overdose rate.
    
    The examination of Median Household Income rates showed a weak positive correlation between income and overdose rates, with a correlation coefficient (r-value) of 0.01, indicating almost no relationship between the two variables. Additionally, the p-value of 0.943 revealed that this correlation was not statistically significant. Any relationship between income and overdose death rates should be attributed to random events rather than a trend between the two variables observed in this section. The flat slope of the regression line further reinforced the conclusion that median household income has a minimal to no influence on overdose death rates across the United States.
    
    The examination of Average Unemployment Rate shows a weak positive correlation between average unemployment rate and overdose deaths per capita. The r-value from the linear regression is 0.093, indicating a very weak positive relationship. The regression analysis also reveals a p-value of 0.515, suggesting that the correlation between unemployment rate and overdose deaths is not statistically significant. A p-value greater than 0.05 means we fail to reject the null hypothesis that there is no significant correlation between these two variables. 
    
    The results of our analysis demonstrates that we must fail to reject all of our null hypotheses. Our data shows that each variable chosen and studied does not have a strong correlation to overdose rates within the US. Scatter plot visualizations of the correlation between these variables (HS graduation rate, median income, and unemployment) and overdose rates, back up our conclusion that our hypotheses must be rejected. All 3 r-values and p-values that we have studied are not strong enough to continue to study these variables in the same capacity. Moving forward, we will be narrowing down the age ranges in this study to 18-29. This is due to recent findings from the CDC that shows that is the age range most susceptible to drug overdoses. Other variables we will study in the next round of testing include Crime Rates, College graduation rates, and number of educational programs per state. We believe this next round of testing will show a stronger correlation to overdose rates. 
 
Slide Deck: https://docs.google.com/presentation/d/1VDoluYLI0uV3aHVuB6uLvtEkH3gigsB2L6oMg0OcEsM/edit?usp=sharing 

