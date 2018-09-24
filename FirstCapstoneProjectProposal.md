Air Quality Analysis

By Ajey Patil 

Introduction

The Objective of this project is to analyse and predict  
Pollution from Air Quality dataset

The Problem

Pollution is measured using Air Quality sensors and analysis of
Air Quality data is required to predict days of week and month
of year when pollution is highest.

The Client

The main clients for this analysis are:

    Citizens of Local Area: The citizens of local area are interested in
    air quality of city so that exposure to pollution can be minimized
    
    Regulatory boards: this analysis will assist in identifying days of week
    and months of year when pollution is likely to be high and give an 
    indication about the source of pollution

The Data

https://archive.ics.uci.edu/ml/datasets/Air+Quality

The dataset contains 9358 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device. The device was located on the field in a significantly polluted area, at road level.


The Approach

The following steps highlight the strategy to be adopted for carrying 
out the analysis for the Capstone project:

    Data Wrangling and Cleaning
        Deal with missing values: Use domain information to determine 
        if missing values should be discarded
        Dropping columns that are irrelevant to the analysis
        Rearrange and transform dataset for cleaner analysis.
        Convert the data into time-series using date-hour information

    Exploratory Data Analysis
        Perform Regression Analysis to determine factors that most influence the
        pollution 
        Identify patterns and correlation between the different variables
        Use data visualization for graphical analysis to answer questions on the dataset

    Predictive Analysis
        Apply machine learning techniques to predict pollution (Carbon-Monoxide
        level) on given day of year and hour of day 

The Deliverables

The deliverables for this project will include a report of all the findings, 
a slide deck and python code, all of which will be published on GitHub.

Specific questions to be explored

1. How does pollution (CO level) vary by day of week ? 

2. How does pollution (CO level) vary by month of year? 

3. Does pollution (CO level) vary co-linearly with other air-quality 
   sensors reading levels ?

4. Based on air quality sensor readings, predict day of week, 
   predict month of year when pollution is highest.

