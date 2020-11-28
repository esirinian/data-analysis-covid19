# The Novel COVID-19 Response on a Global Scale
#### Ayesha Raza, Andrew Hoeft, Eric Sirinian
#### August 7, 2020
## Introduction


This analysis will explore the relationships for both case and death counts with geography, population density, and 
socioeconomic status with normalizations for smoking prevalence, diabetes prevalence, and other environmental controls. 
Ultimately, we seek to expose meaningful hidden dynamics in the novel COVID-19 crisis and extend the general understanding 
of the extent to which vulnerable populations are shouldering a disproportionate share of the overall public health burden.

Our goal, through this analysis, is to garner a better understanding of this infectious disease. Having never experienced 
something of this caliber in the last century, the pandemic has a vice-grip on the world; bringing it to an almost screeching halt. 
With the volumes of data already analyzed and still no solid grasp at how to effectively combat this without self-isolating for weeks 
at a time, we aim to uncover new insights on affected populations around the world. In particular, we are interested building models 
for COVID-19 death rates based on environmental conditions and population dynamics and using those models to back out which dataset 
dimensions are dominant predictors of hieghtened propensity for outbreak.

The data we will use to perform these inferences are provided by Our World in Data (OWID). This aggregator collects publicly available 
information published by official sources on the COVID-19 pandemic and consolidates these data in a single archive.1 Updated regularly, 
the data OWID provide covers most of the world with a majority of their data being no older than 1 week old. While there is no official 
verification of the data, OWID does state that they highlight ambiguities or problems. The data file describes the total number of cases 
and deaths for those who tested positive on COVID-19 by date and country. There are also expectancy and prevalency data on sensitive populations 
who are generally considered to be severely at-risk to complications and elevated mortality rates from COVID-19 (namely, smokers, diabetics, and the elderly).
