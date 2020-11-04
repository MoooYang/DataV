# [Data-Visualization](https://vizhub.com/MoooYang)

## Data
The [National Outbreak Reporting System (NORS)](https://www.cdc.gov/nors/) supports outbreak reporting by partners in state, local, and territorial public health agencies.
It includes different types of Outbreaks such as: Food, Water, Animal, Contact, Environmental, Person to Person, Indeterminate/Unknown.

## Questions & Tasks
* Does the outbreak have the seasonality? Which months have highest frequency?
* How was the distribution of the outbreaks for each type in America?
* Which is the most serious mode? Which state most easily has it?

## Visulizations
### 1. Time-Series Plot
This plot shows how did the number of outbreaks change by time. X-axis is time and Y-axis is the number of outbreaks.\
The pink line is the illnesses, black line is ospitalizations, and the blue line is death. When mouse moves to the line, it will show the exact value at that position.
![image](https://github.com/MoooYang/DataV/blob/master/%E6%88%AA%E5%B1%8F2020-11-04%20%E4%B8%8B%E5%8D%8811.57.18.png)

We can see from the plot that the outbreaks have a significant seasonality. The value reaches the peak at the beginning of the year and drops down till the end of summer. We may conclude that it is more possible to get infected in winter that in summer.

### 2. Distribution Map
This plot shows the distribution of the Outbreaks. Darker color means larger number and it supports interactive functions like showing the number and state name.

![image](https://github.com/MoooYang/DataV/blob/master/%E6%88%AA%E5%B1%8F2020-11-04%20%E4%B8%8B%E5%8D%8811.57.48.png)

### 3. Analysis on Primary Mode
This plot shows how the proportion of different Primary Mode with stack bar plot. 
![image](https://github.com/MoooYang/DataV/blob/master/%E6%88%AA%E5%B1%8F2020-11-04%20%E4%B8%8B%E5%8D%8811.58.03.png)

We can see from the plot that person-to-person takes up most in outbreaks during the year especially in winter. In summer, food almost takes the lead on proportion. We may conclude that person-to-person is the most common infection way. 
## Future Work

### 1. Time-series Plot
User can filter by some categories like "Etology", "State" and "Primary Mode".
![image](https://github.com/MoooYang/DataV/blob/master/01.png)
### 2. Distribution Map
![image](https://github.com/MoooYang/DataV/blob/master/02.png)
### 3. Primary Mode Analysis
Ideally, it will be a dynamic plot. The bars may change by time.
![image](https://github.com/MoooYang/DataV/blob/master/03.png)

### More ideas:
[Interactive details](https://observablehq.com/@vega/vega-lite-annotated-time-series?collection=@vega/vega-lite-api)
