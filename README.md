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

The data contains three parts:<br>
**Enhanced Twitter Archive**(included as csv):The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything.<br>
**Additional Data via the Twitter API**:  Retweet count and favorite count are two of the notable column omissions. You're going to query Twitter's API to gather this valuable data.<br>
**Image Predictions File**: A table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction.
<br>
You can download the ipynb to run it with Jupyter Notebook(don't forget to download csv sheet as well) or view as a HTML.

## Visuals and Findings
1. **The most common dog breeds in our list:** Golden Retriever was the most common dog breeds on We Rate Dogs, accounting for roughly 9% of all posts. The second most common dog type was Labrador Retriever, at around 6%.<br>
2. **Dog ranking by likes and retweets:** Very similar to the most common dog breeds ranking.<br>
3. **Does the most top rated dog get the most likes and retweets?** <br>
-Generally, a higher dog score does not asscoicates with higher view activity. However, the most popular posts with viewers all have highest viewer score.
4. A list of Winner Post of every month by likes and retweets.
