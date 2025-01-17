# <center>**Analysis of drug use in Europe EDA**</center>

[this link](EDA/img/Cannabis_consumption_trend.png)


## Introduction

During the late twentieth century and the early twenty-first century, there has been increased awareness of drug use worldwide. This has led to various measures aimed at controlling the situation, including:

* Prevention strategies through educational campaigns

* Improved access to treatment and rehabilitation

* Stronger drug trafficking controls

* Enhanced research and monitoring

## The Question

Have these measures been effective?

To explore this, this Exploratory Data Analysis (EDA) examines trends in drug use across different countries, specifically focusing on the twenty-first century in the European Union. The analysis also includes data from Norway and Turkey.

This study is based on surveys conducted by the European Union Drugs Agency (EUDA) on the prevalence and patterns of drug use in the general population aged 15-64 (*https://www.euda.europa.eu/data/statistical-bulletin/archive_en*). The surveyed drugs include:

* Alcohol

* Tobacco

* Amphetamines

* Cannabis

* Cocaine

* Ecstasy

* LSD

Additionally, data from Eurostat is used to obtain the Gini coefficient of the countries (*https://ec.europa.eu/eurostat/databrowser/view/tessi190/default/table?lang=en*).

All datasets used in this project can be found at this [this link](EDA/Own_projet)

## Goals of the Analysis:

The following aspects are analyzed in this EDA:

1. Trends in consumption across the selected countries

2. Assessment of consumption by gender

3. Maximum consumption values by country

4. Impact of legalization on consumption trends

5. Evaluation of consumption based on the Gini coefficient

## Table of Contents:

* Introduction
* Import libraries
* Data Loading and Cleaning
    - Data reading
    - Combine DFs and dealing with the missing values
* Descriptive Statistics and graphics
    - Descriptive Statistics
    - Divergence of the data
    - Trend of the data
* Descriptive analysis and graphics with the most updated data
    - Assessment of consumption by gender
    - Maximum consumption values by country
    - Is there an increase in the countries where it is legalized?
    - Evaluation of consumption based on the Gini coefficient
    - Representation of values on a map of Europe
* Final conclusion