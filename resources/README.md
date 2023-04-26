# About the Data
The [dataset](https://github.com/tabburn/CO2-emissions-by-vehicle/blob/main/resources/2023fuelconsumptionCO2.csv) used in this analysis is provided by the Canadian government and the original source can be found [here](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkML0101ENSkillsNetwork1047-2023-01-01). It is currently listed as the English version of '2023 Fuel Consumption Ratings (2023-04-04)'. It provides model-specific fuel consumption ratings and estimated carbon dioxide emissions for new light-duty vehicles for retail sale in Canada. The data is clean and contains no null values.

Here is some more detailed information to help with interpreting the dataset:

Model:
- 4WD/4X4 = Four-wheel drive
- AWD = All-wheel drive
- FFV = Flexible-fuel vehicle
- SWB = Short wheelbase
- LWB = Long wheelbase
- EWB = Extended wheelbase
  
Transmission:
- A = automatic
- AM = automated manual
- AS = automatic with select shift
- AV = continuously variable
- M = manual
- 3 to 10 = Number of gears
  
Fuel type:
- X = regular gasoline
- Z = premium gasoline
- D = diesel
- E = ethanol (E85)
- N = natural gas

| Definitions | |
| -------------- | --- |
| fuel consumption | city and highway fuel consumption ratings are shown in litres per 100 kilometres (L/100 km) - the combined rating (55% city, 45% hwy) is shown in L/100 km and in miles per imperial gallon (mpg) |
| CO<sub>2</sub> emissions | the tailpipe emissions of carbon dioxide (in grams per kilometre) for combined city and highway driving |
| CO<sub>2</sub> rating | the tailpipe emissions of carbon dioxide rated on a scale from 1 (worst) to 10 (best) |
| smog rating | the tailpipe emissions of smog-forming pollutants rated on a scale from 1 (worst) to 10 (best)
