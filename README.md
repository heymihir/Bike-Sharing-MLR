# Bike Sharing Assignment

## Introduction
This assignment focuses on building a linear model to predict the demand for shared bikes.

## Problem Statement
Bike-sharing systems offer short-term bike rentals, allowing users to borrow and return bikes conveniently. BoomBikes, a US provider, faced revenue challenges during the Covid-19 pandemic. To revitalize their business post-lockdown, they aim to gauge future bike demand to prepare for a market rebound.

## Business Goal
The goal is to create a linear model that forecasts bike demand using various factors. This will guide BoomBikes' strategy to meet customer needs effectively and adapt to fluctuating demand, also helping them understand new market dynamics.

## Conclusion
After analyzing the data, the linear regression model accurately predicted bike demand with an R2 Score of 80%.

## Equation of MLR fit line - 

Target Variable = 0.09 + 0.10 * season_2 + 0.14 * season_4 + 0.23 * yr_1 + 0.05 * mnth_8 + 0.11 * mnth_9 + -0.06 * holiday_1 + 0.06 * weekday_6 + 0.05 * workingday_1 + -0.08 * weathersit_2 + -0.29 * weathersit_3 + 0.52 * temp + -0.15 * windspeed
