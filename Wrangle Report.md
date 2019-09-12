# Wrangle Report

**_by Ryan S._**

For this project, I worked with data from a Twitter account called _"WeRateDogs", @dog_rates_. I was provided with some archival data from 2015-11-15 to 2017-08-01. The data was incomplete however, and required using Twitter's API to pull down some additional data. Additionally, I was provided with some data where the images from the Twitter posts was put through a neural network to attempt to identify the breed of dog in the images.

I analyzed each dataset individually first, finding a variety of quality and tidiness issues. I found incorrect data types, duplicate and null values, multiple columns where there should be just one, discrepancies in the ratings, and unnecessary code/strings, just to name a few. I analyzed each dataset thoroughly and made notes of my observations as I went, then combined them at the end of each section. Once I completed the analysis, I combined all my observations into one 'master' list of quality and tidiness issues.

Next, I started on the cleaning process. The first thing I did was merge all three datasets. In the process this eliminated rows that did not line up in all three datasets. There were so many issues to fix I decided to create a table of contents just for that section. For each issue I cleaned, I defined the issue and provided a couple simple lines of code to demonstrate the issue. Then I created a code section where I fixed the issue, and followed that with a test section that proved that the fix was completed. Once the cleaning was complete, I saved off the dataframe into a .csv file.

Lastly, I performed some basic Exploratory Data Analysis (EDA), looking at basic statistics first, then individual fields, and concluded with some bivariate analysis. I made observations of what I found after each variable(s).
