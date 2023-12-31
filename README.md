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
### There were numerous challenges during the process:

### 1. Initially, I encountered limitations with the API usage - I had to stop before finding effective data due to the usage limit. (I solved this problem by creating a new account.)
### 2. Bar information obtained was in the form of a dictionary in a single cell, and separating them was a significant challenge.
### 3. During the EDA process, no obvious variables showed correlation, which had an impact on hypothesis formation. Fortunately, I had two curiosities, although the results showed that they are indeed not correlated.
### 4. I have personal feelings for Riga, but it seems that Riga is not an ideal choice for a project research object: it has a small radius and fewer stations, but a lot of bars. There are many overlapping bars within a 1000m radius. I'm not sure how to handle this.
### 5. I often find that the work in the earlier parts is not ideal when I reach the later parts. I want to make changes, but slight modifications often lead to a lot of errors, which take a long time to fix.

## Future Goals
### If time permits, I would like to process data from several different cities at the same time. After all, data from a small city cannot represent much information. Meanwhile, I want to streamline my code from start to finish. Through this project, I've realized that my practical abilities are lacking. I often know what to do in my mind, but the code I write often lacks detail - an area I need to improve on. It would be better to list out the outline of what needs to be done first, to avoid frequent back-and-forth modifications. This actually wastes a lot of time.
