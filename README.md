




## Tanzanian Wells Project Recommendations 

##### Purchasing airplanes from makers with low percentage of accidents resulting in fatalities and low percentage of totally destroyed aircraft will save money.

## Overview
This project aims to provide your company leadership with the best commercial and private airplane investment recommendations based on the risk of airplane destruction or fatality in an accident.
The purchase price of airplanes can be exorbitant, but the costs of replacement and even more so, fatalities, can be astronomical.  

## Business Understanding
Your company is diversifying its portfolio to include airplanes, but needs to conduct analysis considering the risk to determine the best planes to purchase. 
        
## Data Understanding and Analysis
The dataset was taken from DrivenData, supplied by Taarifa and the Tanzanian Ministry of Water.
    
## Description of data
#### Data shape
The data used for this analysis contains 18017 rows and 21 columns. Columns: Event.Year, Make.Model, Fatal, and Commercial were all generated using the original NTSB dataset; the remaining columns came directly unaltered from the original data set. 
#### Data manipulation
Data were filtered to exclude: (a) amateur built planes, (b) events occurring outside the United States, (c) aircraft other than airplanes (including null values), (d) any event with missing make or model, and (e) any event prior to the year 2000. The top 200 makes were printed out, reviewed for likeness, and combined as needed, e.g., Boeing company, BOEING, and Boeing were combined into one make. 
#### Data limitations        
There are limitations to this dataset and analysis: (a) this database only contains accident/incident data and does not represent successful flights, (b) this analysis was limited to events with "airplane" listed in Aircraft.Category; with a large number (32%) of null Aircraft Category values many probable airplanes not specifically called out as such were dropped from the dataset. (c) this analysis did not filter out the Purpose.of.flight; some values in this column indicate more risky behavior than others and could have impacted the success of the flight. 
#### Data statistics and interpretation
(1) Airbus accidents in the United States resulted in a fatality for less than 1% of of all accidents.

(2) Airbus accidents in the United States resulted in total destruction less than 0.5% of all accidents.

(3) Bombardier accidents in the United States resulted in total destruction just over 2% of all accidents. 
