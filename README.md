# Seasonal Flu Vaccine Analysis

**Author**: [Michael Tsypin](email:mtsypin9@yahoo.com)

## Overview

The purpose of this project is to create a model that helps a pharmaceutical company highlight the key factors of people's reasoning behind receiving the seasonal flu vaccine. Using predictive models, we will analyze data from the National 2009 H1N1 Flu Survery dataset and examine which factors are more likely to lead a person to receive the seasonal flu vaccine.

## Business Problem

A pharmaceutical company wants to understand the driving factors for consumers when developing a new flu vaccine. The key components the pharmaceutical company wants to touch on are people's backgrounds, opinions, and health behaviors regarding the likelihood of them receiving the vaccine. Using data from the National 2009 H1N1 Flu Survey, we can predict who is most likely to receive the vaccine based on these driving factors.

## Modeling

![seasonal vaccine proportion](images/seasonal_vaccine_proportion.png)

Utilizing predictive modeling to find key features for receiving seasonal flu vaccine

## Evaluation

For every increase in 1 square footage of the living area, expect an associated increase of $478 in price

![price_v_sqft_living](images/price_v_sqft_living.png)

For every increase in 1 square footage of the patio, expect an associated increase of $199 in price

![price_v_sqft_patio](images/price_v_sqft_patio.png)

For a house of Fair condition compared to a house of poor condition, we see an associated increase in price of about 16%. For a house of Average condition compared to a house of poor condition, we see an associated increase in price of about 25%. For a house of good condition compared to a house of poor condition, we see an associated increase in price of about 26%. For a house of very good condition compared to a house of poor condition, we see an associated increase in price of about 32%.

![price_v_condition](images/price_v_condition.png)

![price_v_condition](images/price_v_condition.png)

Confusion matrix results

## Conclusion



## For More Information

See the full analysis in the [Jupyter Notebook](home_renovation_analysis.ipynb) or review [Presentation](home_renovation_presentation.pdf)

## Repository Structure

```
├── data
├── images
├── .gitignore
├── README.md
├── seasonal_flu_vaccine_analysis
└── seasonal_flu_vaccine_presentation
```
