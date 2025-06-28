# AIRCRAFT RISK ANALYSIS
***
![alternative](images\aero.jpg)
## OVERVIEW
This project analyzes aviation accidents from the National Transportation Safety Board(NTSB), covering incidents from 1962 to 2023. The goal is to identify low risk aircrafts that the company can consider for purchase as it ventures into commercial and private enterprise by cleaning, sorting, grouping, aggregatting data, we extract insight for strategic decision making of aircraft acquisiotion.

## BUSINESS PROBLEM
The company is entering the aviation industry. However, they lack insight into the historical safety performance of different aircraft. The goal of this analysis is to identify aircrafts with low accidents, considering the given factors and provide recommendations on the safest and suitable aircrafts.

## DATA
The dataset comes from National Transportation Safety Board(NTSB) and contains aviation accidents from 1962 to 2023. the dataset contain information on:

1. "Event.Date": showing the date of the incident.
2. "Make", "Model": showing manufacturer and aircraft model.
3. "Injury Severity" : Fatal, Serious, minor injuries.
4. "Total Fatal Injuries", 'Total Serious Injuries', 'Total Minor Injuries', 'Total Uninjered'
5. "Purpose of flight": Purpose such as business, personal
6. "Weather condition": Representing the Instrument and Visual Meteorogical Conditions(IMC,VMC)
7. "Broad phase of flight" : such as Takeoff, cruise, landing...
8. "Aircraft damage": extent of damage of the the aircraft
9. "Engine Type",
10. "Number of Engines": showing how many engines each aircraft had

## METHODS
This project uses descriptive analysis and predictions to show insight on aircraft risk

## RESULTS
* From my first Data analysis of aircraft Model by the number of incidents, I figured that Cessna 152 model have the highest number of accident counts. Considering Piper, model PA-28-140 have the leading accident counts interms of Piper make.
![alternative](images\bynumber.png)
* Comparing the Fatality rate agaist Make-Model, I figured that Boeing 737 model have the highest fatality rate, followed by Boeing 737-200 model.
![alternative](images\byfatality.png)
* Purpose of flight.-Personal flights like Cessna 152, 172, 172N models reported higher accident counts.
![alternative](images\purpose.png)
* Aircrafts with 1 number of engine showed the highest accident counts
![alternative](images\engine.png)

## Link to Tableu dashboard
* Here is the link to tableu dashboard [View the dashboard](https://public.tableau.com/app/profile/meshack.mboya/viz/AviationAccidentsDataAnalysis_17511174111600/AicraftAccidentsAnalysis)

## CONCLUSIONS
* Comparing the Fatality rate by Make and Model, Boeing 737 model showed the highest fatality rate. Boeing aircrafts are larger in size and are most commonly used for commercial services, they carry a lot more passengers compared to other aircrafts Makes like Cessna, Piper, Beech. This increases the mortality rate with few accident counts.

* Purpose of flight. Cessna 152 model reported the highest accident counts with reduced fatility rate, mainly because they are commonly used for personal reasons and carry fewer passengers compared to commercial aiplanes.

* Number of engine. aircrafts with multi-engines showed low accident counts compared to aircrafts with 1 engine, projecting the ability of an aircraft to continue flying after one engine failure.

## RECOMMENDATIONS
1. The company should invest in aircrafts with multi-engines i.e 2,3 engines as they show reduced accident rate from the analysis
2. For commercial airlines the company should take note of Boeing 737, 737-200 models high fatality rate and prefer other Boeing models. 
3. For personal airplanes the company should take note of Cessna 152 model highest accident counts and go with other models like Cessna 182, 150 models that display reduced accident counts