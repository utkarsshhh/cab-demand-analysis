# cab-demand-analysis


### This code file here performs data analysis on two weeks of data from a cab service with mobile web application


## Introduction

I have built this project based on the data provided by [Stratascratch](https://www.stratascratch.com) as part of a Data project. It provides the data regarding the online app usage and cab trips of two weeks and this code analyzes the data to answer the following business questions:

1. On which date were there most completed trips ?
2. What was the highest number of trips completed in 24 hours ?
3. Which hour of the day had the most requests over two weeks ?
4. What percentage of all zeroes occurred on the weekend ? (All Zeroes mean the user didn't see any cabs)
5. What is the weighted average ratio of completed trips per driver during the two week period?
6. Which is the busiest working shift in two weeks. (Assuming the shift to be for 8 hours and each driver works in the same shift) ?
7. Does the driver supply always increases when demand increases during the two week period ?
8. In which 72 hour period is the ratio of Zeroes to Eyeballs the highest? (Eyeball means the number of users that opened the app)
9. Which hour of the day is the busiest hour where we can add new drivers ?
10. During which hour of the day are the supply and demand both at minimum ?

__The above questions will help analyse the supply and demand of rides and help the business to make better use of resources which make a difference in the profits.__



## Usage

### Installation
The code is present in a Jupyter Notebook __Data_Analysis.ipynb__ and requires Python 3.9 to run it. The Jupyter Notebook can be run in the browser or can be installed from [here](https://jupyter.org)

### Data
The data is present in the __datasets__ folder in the root directory. The data is not present in the repository.

### Libraries
The following libraries have been used in the code:
1. [pandas](https://pandas.pydata.org)
2. [datetime](https://docs.python.org/3/library/datetime.html)
3. [matplotlib](https://matplotlib.org)
4. [numpy](https://numpy.org)


## Result

The data has been wrangled according to the use cases of the business. The plots using pandas and matplotlib have been used to visualise the analysis of the data and provide answers relevant to the business. We have a good inference about the service usage over different points of time during a day or a week.



