# Daily Step Analysis

This repository is for Coursera, Reproducible Research: Peer Assessment 1, about Daily Step Analysis

## Introduction to the Project

The purpose of this project is to analyze the provided data set and find out answers to assignments required as following.

*Assignment Instructions:*

1. Code for reading in the dataset and/or processing the data 
2. Histogram of the total number of steps taken each day 
3. Mean and median number of steps taken each day 
4. Time series plot of the average number of steps taken 
5. The 5-minute interval that, on average, contains the maximum number of steps 
6. Code to describe and show a strategy for imputing missing data 
7. Histogram of the total number of steps taken each day after missing values are imputed
8. Panel plot comparing the average number of steps taken per 5-minute interval across weekdays and weekends 
9. All of the R code needed to reproduce the results (numbers, plots, etc.) in the report

The dataset is provided by Cousera weblink, it can be downloaded via the website.

## Files in the repository

Following files are inlcuded in this repo: 

- The README.md gives the brief introduction about the implementation.

- The Rmd script DailyStepAnalysis.Rmd is created for data cleaning and analysis.

- The DailyStepAnalysis.html is the output result from previous Rmd file. It is also published under Rpubs as https://rpubs.com/KeepLearning/644419.

- The figure DailySteps_xx.png records the figure results for most required items.


## Details in Rmd script

The data set provided by the Coursera weblink are used for analysis. 

Details implemented in run_analysis.R:

*Preparation*
- Download the raw data from provided weblink, through download.file.
- Unzip the download file, through unzip. 
- Read data from downloaded compressed package. 

*Data handling*
- Convert varabile date format from character to date
- To handle the data as assignment instructions, see datails in related Rmd file.
