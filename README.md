![images.jpg](Img_1.jpg)

## Title: Data-Wrangling Analysis On WeRateDogs Twitter Account Tweets From 2015 -2017
### Presented by: Ayobami Alaran
### Date: 25-06-2022

## Introduction

WeRateDogs is twitter account with username dog_rates where people post tweets about dogs and rate them.
[click here](https://twitter.com/dog_rates) for more info on the twitter account

Data-Wrangling Analysis process which includes **Gathering, Assessing and Cleaning** was performed on the data obtained from the twitter account using three various method of gathering data for the gathering stage;
>- data_1 = twitter_archive_enhanced.csv (which is already available for download in the classroom)
>- data_2 = image_predictions.tsv (queried from the udacity server using request library)
>- data_3 = twitter_data.json (scraped from twitter with twitter Api v1)

## Problem
Tweet data is unclean, messy and unorganised, no accurrate or reliable insights can be obtaine from the data

## Solution
Gather, clean, organise and tidy the messy data to extract meaningful insights 

### Analytical goals 
>- Assess the data for tidyness and quality issues 
>- Document the issues 
>- Fix and clean the issues documented 
>-Analyse the clean data for interesting facts 
For the Wrangle report [Click here](https://github.com/Ayobami6/Tweet-Data-Analysis/blob/main/wrangle_act.pdf)



### Project Objective
Perform data-wrangling analysis on the WeRateDog tweets from 2015 - 2017, which involves gathering, assessing and cleaning the datas 

### Assessing The Data

The Gathered data was assessed visualy using Ms-Excel Spreadsheet and .head and .tail function in python to some quality issues(content issues) and tidiness(Structural issues). 
Moreso, the dataset was also assessed programmatically using some funtions in python to further investigate te dataset for hidden issues.

### Cleaning 
After assessing and documenting the detected issues, the cleaning stage was initialize to fix the issues highligted to get the dataset ready for analysis by writing and automating some python codes to fix the issues. 

## Findings and Conclusion 
* From the result of the analysis it was observed that the dog specie with the highest prediction count in prediction 1 is the Golden_Retriever with the highest count of 150
* The result of the analysis reveals the tweet with highest retweet count is **Here's a doggo realizing you can stand in a po...** with the retweet count of **70770** among all other tweets between the 2015-2017
* From the analysis it was revealed that the most frequent tweet source for dogs' tweet between 2015 - 2017 is twitter for iphone.
For the act report [Click here](https://github.com/Ayobami6/Tweet-Data-Analysis/blob/main/act_report.pdf)

### Project Help Sources 
Analysis and some syntax ideas was acquired from ALX DA Udacity classroom, data science community such as stackoverflow and geeks4geeks,datacamp and some code documentation websites such as tweepy docs and regular expression docs.
