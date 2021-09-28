# Fall20 DSCI511 - Data Collection Project
## Topic: US 2020 General election polling data study

Research Topic
Our research topic is about investigating the reliability and predictability of political polling in the US, by analyzing general variation trends of the population’s election preference, and identifying major social/economic factors affecting these trends. A data set was built through acquiring and cleaning three major parts from field of US unemployment rate, US COVID-19 cases, and US polling data.

Source of Datasets and Observations
The data consists of three major parts, US 2020 general election polling data from FiveThirtyEight website, unemployment rate statistics from (XXX), and COVID-19 caes from (XXX). The outcome data set focus on seven swing states of California, New York, Wisconsin, Florida, Pennsylvania, Texas, and Georgia. Time span wise is considered from beginning of 2020 to October of 2020 and unit is half month.

Limitation and challenge
One of the challenge for the polling data is the accuracy and continuity. FiverThirtyEight website actually use aggregating polling data from numerous pollster. Based on different hitorical accuracy of pollsters, sample size, their methodology to conduct data, and several other aspects, graded them through grade A to grade D, FiveThirtyEight website didn't make it publicize their methodology for putting weight on each source of pollster and how it affect the overall polling data. In our data set, we simply average the percentage data for two major candidates Trump and Biden for each segment of the month, and by seven diffrent state. Thus the accuracy would be lower than expected. Also becasue the source csv file downloaded from FiveThirtyEgiht websites contains periods of time from each pollster, the data is discrete and not continued. Meaningthe the final cleaned data set has null value for some of the month segment of diffrerent state.
