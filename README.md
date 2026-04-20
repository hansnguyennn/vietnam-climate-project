# Vietnam Climate & Disaster Patterns

**PHY-231 Think Like a Data Scientist — Final Project**
**Student:** An Nguyen

## Live Site
[https://hansnguyennn.github.io/vietnam-climate-project](https://hansnguyennn.github.io/vietnam-climate-project)

## Overview

This project investigates how monsoon rainfall, river behavior, and natural disasters connect across Vietnam using three Kaggle datasets spanning 1901–2023.

## Research Questions

1. Does more rain in a given month mean more disasters that month?
2. Do provinces with the most volatile rivers get hit harder by disasters?
3. Do rivers have a "tipping point" — a level where flooding becomes dangerous?
4. Has Vietnam's rainfall pattern shifted over the past 90 years?

## Datasets

| Dataset | Source |
|---|---|
| Rainfall & Temperature Vietnam 1901–2020 | [Kaggle](https://www.kaggle.com/datasets/patricklford/rainfall-and-temperature-vietnam-from-1901-to-2020) |
| Mass Disasters in Vietnam 1900–2024 | [Kaggle](https://www.kaggle.com/datasets/patricklford/mass-disasters-in-vietnam-from-1900-to-2024) |
| Water Levels of Rivers in Vietnam | [Kaggle](https://www.kaggle.com/datasets/suthcong/water-levels-of-rivers-in-vietnam) |

## Tools Used

- Python, pandas, matplotlib, sqlite3
- Jupyter Notebook
- HTML (website)

## Key Findings

- Rainfall and disasters both peak in the Aug–Nov window, but deaths peak in September — not the rainiest month
- Central coast provinces (Hue, Quang Nam) appear most in disaster records despite moderate river sizes — geography matters more than river scale
- Song Thu Bon and Song Ta Trach exceed their danger thresholds ~7% of the time, equivalent to ~25 dangerous days/year
- November has gained +11.6mm of rainfall over 90 years, extending the deadliest part of the disaster season
