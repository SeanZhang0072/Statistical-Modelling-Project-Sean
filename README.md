# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
### In this project, my goal is to request data from an API according to specific requirements and to perform statistical analysis based on the acquired data.

## Process
### Step 1: First, I obtained information on shared bicycle stations in the city of Riga from the CityBike website, including station names, geographical coordinates, and the number of available bicycles.
### Step 2: Using an API (I chose Foursquare after comparison), I sought information on specific places within a 1000m radius of each bicycle station. I chose bars because I was curious whether people might choose to ride bicycles to drink or ride home after drinking, to avoid drunk driving.
### Step 3: The two sets of data were then restructured to consolidate their information into a single table.
### Step 4: EDA was performed with an attempt to observe correlations between the data. The processed data was then put into an SQLite3 database, with searches made using SQL syntax.
### Step 5: A regression model was established and the results were analyzed.

## Results
### Riga had a total of 41 shared bicycle stations based on the CityBike search. Most of them had 0-3 available bicycles. ![Alt text](https://drive.google.com/uc?export=view&id=1FDu9IgKGJoSr4jKdgL1CGkwHG5_4C6m7)
![Alt text](https://drive.google.com/uc?export=view&id=1W8tkRmUyQ1-8F5OaDBNexSUIXa2kYmrl)
### In terms of bars within a 1000m radius of bicycle stations in Riga, 38 stations were surrounded by more than 10 bars, with 28 stations having exactly 10 bars. ![Alt text](https://drive.google.com/uc?export=view&id=1Z1VRbSkmb61E9Ll2Re_7DVsnSD_25DmV)
### No rating information could be found, so rankings could not be established.
### In the final regression model, when analyzing the correlation between the number of available bicycles, the number of nearby bars, and their average distance, the result indicated almost no correlation.![Alt text](https://drive.google.com/uc?export=view&id=1bYXjCoS2a58ELKX4jc4VKKL2DrtdXG4A)
![Alt text](https://drive.google.com/uc?export=view&id=10fn6P6c6BE7vUYgYam_lmjmTk9C5Z8Kn)

## Challenges 
(discuss challenges you faced in the project)

## Future Goals
(what would you do if you had more time?)
