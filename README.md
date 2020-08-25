# Communicate-Data-Findings
## Introduction
With interstate travel restrictions and declined travel within the United States, it is interesting to discover the trends of the airline industry. Do we get fewer flights this year? Are there fewer delays this year? Which State or Airline Company takes the greatest impact from the travel restriction? In this project, I will process US flight data and find out the answers for you!
## About this project and Udacity Data Analysis Nanodegree Program
This project aims to aid the learning process of communicating data findings. In this project, I will be using Data Wrangling, Univariate Exploration, Bivarite Exploration and Multivariate Exploration to create visualization from raw data.<br>
The data used in this project is called [On-Time : Reporting Carrier On-Time Performance (1987-present)](https://www.transtats.bts.gov/Fields.asp). This datatable contains basic information of flights(Time, Origin, Destination, Delay, Cancel information) from 1987 to 2020 April. The data picked for this project are two seperate sessions: 2019.04 and 2020.04. The indentical period the different years are selected to compare the difference in flight numbers, delays, cancellation, etc.

## How to run this project
The coding environment is Python, including the following:
<li>Numpy</li>
<li>Pandas</li>
<li>Seaborn</li>
<li>Matplotlib</li>
<br>

The project requires the following files to run:
<br>
<li>Dateset(zip):Contains 2019 and 2020 data in separate files.</li>
<li>exploratory.ipynb:  The raw python code with graphs you run with Jupyter Notebook. Also includes a HTML version.</li>
<li>exploration_template.slides.html: A HTML format slide. You can use your arrow key to read through it(recommend you zoom to 50% to read it). Also includes a ipynb version.</li>

## Visuals and Findings
**Hypothesis:** I expect the flights in 2020.4 are less likely to be delayed, more but likely to be cancelled comparing to 2019.4 due to travel restriction. I expect the cause of delay will be quite different.<br>
**Actual Finding:** The number proved my prediction for the flight delay and cancellation. However, the cause of delay seems similar to last year. Moreover, the pattern of delay time is a bit different in terms of distibution and scale.

Other two visuals are **i. 2019 vs 2020 comparsion & ii. delay factors and distribution**

### References:
Add percentage on seaborn:https://stackoverflow.com/questions/31749448/how-to-add-percentages-on-top-of-bars-in-seaborn<br>
Round percentage in chart:https://stackoverflow.com/questions/43675014/panda-python-dividing-a-column-by-100-then-rounding-by-2-dp<br>
Set Xticks in Facet Grid:https://stackoverflow.com/questions/43727278/how-to-set-readable-xticks-in-seaborns-facetgrid
