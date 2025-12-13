# Predicting Demonstration Size on Salience and Demographic Characteristics

## GW DATS 6103: Introduction to Data Mining Final Project

### Alexander D. Silberman

### 2025-12-12

In recent years, demonstrations in the US have grown in both number and scale (*Crowd Counting Consortium*, 2024). Being able to predict the scale of future demonstrations would allow for a more efficient distribution of resources and would enable protesters, government institutions, first responders, and news organizations—among others—to better prepare for what is to come.

In an analysis of Chilean demonstrations between 2000 and 2012, Somma & Medel found that demonstrations targeting broader issues had larger crowd sizes (2018). In other words, demonstrations surrounding issues that larger portions of the population care about tend to be larger in scale. An opposing arrow of causality was drawn by Carey, Jr. et al. (2014), which pointed to a rise in the salience of immigration among U.S. Latinos following the 2006 immigration protests. In either case, there is some evidence to suggest that increased salience corresponds with increased crowd sizes, and may thereby be useful in predicting such.

In general, however, in spite of the importance of this topic, little work has been done on predicting the size of demonstrations, as noted by Somma & Medel (2018, pp. 2–3).

The SMART question at the heart of this analysis is as follows: is it possible to predict the size of crowds at demonstrations—as measured in either raw number or magnitude—for the years 2017 and 2018 based on salience of the issue(s) at hand, as indicated by the percent of the population who labeled that category Most Important Problem that year, and demographic data at the county level for that year, as sourced from the American Community Survey (ACS) 1-year estimates?