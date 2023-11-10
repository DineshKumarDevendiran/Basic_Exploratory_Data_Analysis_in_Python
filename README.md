# Data-analysis-
# Insights into Unicorn Companies

## Introduction

This Jupyter Notebook explores a dataset containing information on over 1,000 unicorn companies. The dataset includes details such as industry, country, year founded, and select investors. The goal is to gain insights into how and when companies reach the prestigious unicorn status and to provide recommendations for investment firms.

## Table of Contents

1. [Overview](#overview)
2. [Data Handling](#data-handling)
3. [Results and Evaluations](#results-and-evaluations)
    - [1. Time to Reach Unicorn Status by Industry](#1-time-to-reach-unicorn-status-by-industry)
    - [2. Valuation by Industry](#2-valuation-by-industry)
    - [3. Insights from 2020](#3-insights-from-2020)
    - [4. Compare Valuation in 2020 and 2021](#4-compare-valuation-in-2020-and-2021)

## Overview

The dataset contains information on 1,074 unicorn companies with 10 attributes, including company name, valuation, date joined, industry, city, country/region, continent, year founded, funding, and select investors.

## Data Handling

- Converted the 'Date Joined' column from object to datetime.
- Separated the 'Year Joined' from the 'Date Joined' column.
- Calculated the time it took for each company to reach unicorn status.
- Handled negative values in the 'Unicorn Status' column, indicating a global outlier.

## Results and Evaluations

### 1. Time to Reach Unicorn Status by Industry

- Grouped the data by industry and plotted the maximum time it took for companies to reach unicorn status.

### 2. Valuation by Industry

- Converted the valuation column to numeric format and plotted the valuation of each industry in billion USD.

### 3. Insights from 2020

- Filtered the dataset for the year 2020 and visualized the number of companies in unicorn status each week.

### 4. Compare Valuation in 2020 and 2021

- Concatenated datasets for 2020 and 2021, grouped by quarter, and plotted the average valuation for each quarter.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/unicorn-companies-analysis.git
