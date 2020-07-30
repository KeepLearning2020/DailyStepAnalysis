# Daily Step Analysis

This repository is for Coursera, Reproducible Research: Peer Assessment 1, about Daily Step Analysis

## Introduction to the Project

The purpose of this project is to analyze the provided data set and find out answers to assignments required as following.

1. which types of events (EVTYPE) are most harmful with respect to population health
2. which types of events have the greatest economic consequences

The dataset is provided by Cousera weblink, it can be downloaded via the website.

## Files in the repository

There are three files in this repo: 

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
