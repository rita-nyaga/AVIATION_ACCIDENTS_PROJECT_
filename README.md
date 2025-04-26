# AVIATION ACCIDENTS
## OVERVIEW
### This project aims at diving into the aviation industry and identifying the major risks involved and coming up with mitigating measures

## BUSINESS PROBLEM
### The company is expanding and diversifying its portfolio. They are interested in purchasing and operating airplanes for commercial and private enterprises. Its a industry whose risks are not well known. The task is to determine the key risk factors. 

## DATA UNDERSTANDING
### The dataset to use is - AviationData.csv from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023. The data includes civil aviation accidents and selected aincidents in the United States and international waters. We will be using specific columns for our data analysis, some include, Engine.type,Weather.Conditions, Location, and few others. 

## DATA ANALYSIS
### Pandas is the main library and matplotlib for visualizations. Refer to the .ipynb file.

## RESULTS

### The results of the findings are summarized in visualizations below
![Engine type]('Images/engine_type.png')
![Weather conditions]('Images/weather_conditions.png')
![location]('Images/locaton.png')
![Trends over time]('Images/trends_over_years.png')

## CONCLUSION AND RECOMMENDATIONS
### There are soo many risks in the business, we have only highlighted three, and have come up with the following recommendations;

### 1. All engine types have recorded accidents but the Turbo Fan engine has the least number of injury rates. Its a safer engine as compared to the rest.If we purchase arcrafts with this kind of engines then we are assured of safer flights.

### 2. We have to be on the lookout on weather.From our data we got a very interesting find,contrary to what we know that bad weather causes most accidents, our data states differently.The VMC - Visual Metrological Condition,which involves clear skies no heavy rains and clear visibility, has the highest number of accidents. This shows that mostly, its not really about the weather, its about the pilot, the engine type, the plane model and make etc. Also soo many planes are in the air during this time. Setting up proper control departments to monitor the routes would help mitigate this risk. Also competent pilots

### 3. There are geographical locations that have very high injury rate. When a plane crushes there the results are more fatal. From the bar chart top 10 locations are sighted, top of them being,Ankorage Ak. Avoiding such routes would put us n lower risk.