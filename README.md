# Datatalks MLZoomCamp 2025 Midterm Project
The midterm project of Datatalks MLZoomCamp 2025 (Sep to Jan 2026)
Currently Cloned onto Local PC.

## Package manager used
I have used conda as the package manager. Therefore, an environment.yml file has been created

## Required Libraries (so far) are
1. Numpy
2. scikitlearn
3. pandas
4. ML model libraries

## Optional Libraries are
1. KaggleHub

## Variable pre-start entries
A properties file or a json file containing following entries (at least):
1. Data from URL or no
2. Data file location (URL or local dir path)
3. Data file name
4. Target Feature name and type

## Current progress
Learning how to do stuff locally

## Current Situation
Not sure if the dataset I have selected is worth it. Still researching. May switch dataset

## Dataset
The dataset I have so far is 
    Date:'solar radation'
    Filetype: 'csv'
    Description: 'will be added'

## Target
To predict or calculate solar radiation based on other features (provided within that timeframe only)

## Next step
1. To calculate total sunlight time from sunset, sunrise difference ✔️
2. The time data was measured has impact but by how much
3. Create Fractional Hour: Combine them into one feature.
$$\text{Recorded\_Fractional\_Hour} = \text{recorded\_hour} + \frac{\text{recorded\_minute}}{60} + \frac{\text{recorded\_second}}{3600}$$
3. To plot and get the correlation between each feature ✔️
4. How much impact each feature has on target feature ✔️
5. Some features have only one data, so remove them. Like year, seconds, etc ✔️
6. Drop column sunset and sunrise data since daylight time calculated
...
N. Which regression to use