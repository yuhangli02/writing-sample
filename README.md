HW06: Generating reproducible social science research
================
Yuhang Li
7/10/2023

## Description of repository

This repository is used for the data analysis project for HW06. My
project aims to analyze civil asset forfeiture data provided by
[Institute for
Justice](https://ij.org/report/policing-for-profit-3/policing-for-profit-data/)
to answer the research question “What trends does revenue generated from
civil asset forfeiture follow, and how are forfeiture funds allocated?”

## 1. Description of data sets used

I used revenue and expense data sets at the national level and
specifically for Illinois.

-   **forfeit_raw** contains the raw data sets downloaded from the
    [Institute for
    Justice](https://ij.org/report/policing-for-profit-3/policing-for-profit-data/)
    website.
-   **forfeit_raw/National_Expense/National Expense.csv** is the
    national civil asset forfeiture funds expenditure data.
-   **forfeit_raw/National_Revenue/National_Revenue.csv** is the
    national revenue data for forfeiture funds.
-   **forfeit_raw/State_Expense/ILexpense.csv** is the expenditure data
    for civil asset forfeiture funds in Illinois
-   **forfeit_raw/State_Revenue/ILrevenue.csv** is the revenue data for
    forfeiture funds in Illinois.
-   Each file in **forfeit_raw** contains the original README.txt with
    descriptions of variables. Note: some variables in the raw dataset
    are not described in README.txt. If any of these variables are used
    in **data_analysis.Rmd**, it will be described in comments.  
-   **forfeit_cleaned** contains three cleaned data sets that is used in
    my analysis.
-   **forfeit_cleaned/national_exp_cleaned.csv** is the cleaned national
    expenditure data.
-   **forfeit_cleaned/national_rev_cleaned.csv** is the cleaned national
    revenue data.
-   **forfeit_cleaned/IL_cleaned.csv** is the cleaned data for Illinois
    with expense and revenue information joined.

## 2. Description of scripts

-   My project contains three main scripts : **data_cleaning.R**,
    **data_analysis.pdf**, and **data_report.md**.
-   **data_cleaning.R** is my script for importing and cleaning the raw
    data sets in **forfeit_raw**.
-   **data_analysis.pdf**, generated from **data_analysis.Rmd**,
    contains my exploratory data analysis code and graphs for this
    project.
-   **data_report.md**, generated from **data_report.Rmd**, is my final
    data analysis report that contains explanation and output to answer
    the research question.
-   The files should be executed in the following order from first to
    last: **data_cleaning.R**, **data_analysis.Rmd**, and
    **data_report.Rmd**.
-   **data_analysis_files/figure-gfm** contains the graphs and tables
    generated from **data_analysis.Rmd**.
-   **data_report_files/figure-gfm** contains the graphs and tables
    generated from **data_report.Rmd**.

## 3. Packages required

The R packages required are `tidyverse`, `knitr`, `scales`, and
`huxtable`.

## 4. Reflections

The hardest part of this homework was the workflow of determining the
data set to use, finding an interesting research question, and plan the
data cleaning and graphs. I spent a long time exploring different data
sets and formulating potential research questions. After I solidified my
research question, I found it challenging to plan out the method of
analysis. Sometimes, my variables were difficult to manipulate, and I
had to think of multiple ways to create the most representative graphs.

After manipulating the data sets for some time, I became more familiar
with the variables and was able to generate sub-questions throughout the
analysis process. The most enjoyable part of this project was finding
out more information about a completely unfamiliar topic through
applying the tools learned in class. After researching multiple websites
and articles, I gained interesting knowledge on civil asset forfeiture
policies.

I used *R for Data Science*, Stack Overflow, and Google as resources for
coding.
