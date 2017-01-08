# Exploring-Gun-Deaths-in-the-US
Use of list compprehensions, modules, and datetime package to find patterns in US gun death data.

Introduction:-

The dataset came from FiveThirtyEight, and is stored in the guns.csv file. It contains information on gun deaths in the US from 2012 to 2014. Each row in the dataset represents a single fatality. The columns contain demographic and other information about the victim. 
I already explored gun deaths by race. However, my analysis only gives me the total number of gun deaths by race in the US. Unless we know the proportion of each race in the US, we won't be able to meaningfully compare those numbers. What we really want to get is a rate of gun deaths per 100000 people of each race. In order to do this, we'll need to read in data about what percentage of the US population falls into each racial category. Luckily, we can import some census data to help us out.

The data also contains information on the total population of the US, as well as the total population of each racial group in the US. The data is stored in the census.csv
