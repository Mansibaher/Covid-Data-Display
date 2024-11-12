# Covid-Data-Display
# COVID-19 Data Display Project

This project is a Python-based data visualization tool that displays COVID-19 data for India. Through graphs and bar charts, it provides insights into the spread and current status of COVID-19 across various states in India, facilitating a deeper understanding of the pandemic's impact.

## Table of Contents
- [Introduction]
- [Data Sources]
- [Data Description]
- [Features]
- [Setup and Installation]
- [Usage]
- [Conclusion and Future Work]
- [References]

## Introduction

COVID-19, caused by the SARS-CoV-2 virus, has significantly impacted India, prompting the need for data analysis tools to monitor and visualize its spread. This project allows users to display COVID-19 data in line and bar graph formats, helping users analyze various aspects of the pandemic, such as:
- Current COVID-19 situation in India
- State-wise comparisons
- Date-wise new cases, confirmed cases, recovered cases, and deceased cases

## Data Sources

The COVID-19 data used in this project is sourced from:
- [api.covid19india.org](https://api.covid19india.org)
- [Ministry of Health and Family Welfare, Government of India](https://www.mohfw.gov.in)
- Additional information and facts from [Wikipedia](https://en.wikipedia.org/wiki/COVID-19)

## Data Description

The dataset is a CSV file with records from January 1, 2020, to July 26, 2021. Key columns used in this project:
- **Date**
- **State**
- **Confirmed**
- **Recovered**
- **Deceased**

A new column, `NewCount`, is calculated as the difference between the "Confirmed" and "Recovered" cases.

## Features

1. **Line Graphs**: Displays COVID-19 trends for selected states or all of India over time.
2. **Bar Graphs**: Provides a state-wise comparison of COVID-19 case counts on a specific date.
3. **User-Driven Visualization**: Users can select data for specific states and date ranges for personalized analysis.



