# The Effect of Recreational Marijuana Legalization on Violent Crime Rates

## Overview
This project analyzes whether the legalization of recreational marijuana is associated with changes in violent crime rates across U.S. states. Using a **Difference-in-Differences (DID)** causal inference framework, we compare states that legalized recreational marijuana to carefully selected control states that did not.

## Research Question
Does recreational marijuana legalization cause an increase in violent crime rates?

## Methodology
- Difference-in-Differences regression analysis
- Treatment vs. control state pairs matched on regional and demographic similarity
- Monthly violent crime rates per 100,000 residents
- Parallel trends assumption checked for each state pair

## Crimes Analyzed
- Aggravated Assault
- Homicide
- Rape
- Robbery

## Data Sources
- FBI Crime Data Explorer (2006–2024)
- U.S. Census population data (for per-capita normalization)

## Key Findings
- Results vary by state and crime type
- Some state pairs show statistically significant increases post-legalization
- Other comparisons show no effect or decreases
- Many state pairs fail the parallel trends assumption and are excluded

## Limitations
- Seasonality in crime
- Concurrent policy changes (e.g., alcohol privatization in Washington)
- Broader social and economic confounders

## Tools & Technologies
- Python (pandas, statsmodels, matplotlib)
- Google Colab
- Difference-in-Differences regression

## Authors
- Shivani Rao  
- Dunovan Rodgers  
- Cassie Semenas  
- Sara Young  

## Course
GENBUS740: Experiments and Causal Methods for Business Insights  
University of Wisconsin–Madison
