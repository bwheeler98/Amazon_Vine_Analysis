# Amazon_Vine_Analysis

## Overview

The purpose of this analysis was to use PySpark to read in 'Big Data' and perfom the ETL process.  The analysis also involved SQL and Amazon Web Services to store the data in a more efficient way.  There are tons of amazon product reviews, so using PySpark, SQL, and AWS was the best option for cleaning and analyzing the data.

## Results

### Vine Reviews

<img src="https://github.com/bwheeler98/Amazon_Vine_Analysis/blob/a42950738516660956075d96702ee9e46b376164/Screen%20Shot%202022-07-10%20at%206.26.48%20PM.png" width="500" height="350">

There were 312 Vine reviews.

### Non-Vine Reviews

<img src="https://github.com/bwheeler98/Amazon_Vine_Analysis/blob/a42950738516660956075d96702ee9e46b376164/Screen%20Shot%202022-07-10%20at%206.27.38%20PM.png" width="500" height="350">

There were 57,608 Non-Vine reviews.

### 5 Star Reviews

<img src="https://github.com/bwheeler98/Amazon_Vine_Analysis/blob/a42950738516660956075d96702ee9e46b376164/Screen%20Shot%202022-07-10%20at%206.28.23%20PM.png" width="500" height="350">

There were 30,772 total five star reviews.

### Percentage of Paid 5 Star Reviews

<img src="https://github.com/bwheeler98/Amazon_Vine_Analysis/blob/a42950738516660956075d96702ee9e46b376164/Screen%20Shot%202022-07-10%20at%206.29.02%20PM.png" width="500" height="350">

The percentage of paid five star reviews was 53.9%.

### Percentage of Unpaid 5 Star Reviews

<img src="https://github.com/bwheeler98/Amazon_Vine_Analysis/blob/a42950738516660956075d96702ee9e46b376164/Screen%20Shot%202022-07-10%20at%206.29.12%20PM.png" width="500" height="350">

The percentage of non-paid five star reviews was 51.5%.

## Summary

There does not seem to be any positivity bias for reviews in the Vine program, for there were only 312 Vine reviews compared to 57,608 non-Vine reviews.  There is not a big enough sample to determine if the Vine reviews are biased.  One way to improve this study would be to use NLP to analyze the 'review headline' and 'review body' columns.  
