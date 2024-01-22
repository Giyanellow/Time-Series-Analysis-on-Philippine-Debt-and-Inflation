﻿# Time-Series Analysis on the Philippines' Inflation Rate (1960-2021)

## Table of Contents
- [Introduction / Problem Statement](#introduction--problem-statement)
- [Gathered Data / Dataset](#gathered-data--dataset)
- [Tools and Libraries](#tools-and-libraries)
- [Installation](#installation)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction
The analysis involves two main datasets:

- **Inflation Data**: This dataset contains the inflation rates for the Philippines over several years.
- **External Debt Data**: This dataset includes information about the total external debt stocks for the Philippines.

The primary objective is to combine these datasets, clean the data, and analyze the relationship between inflation and external debt. Additionally, the analysis includes identifying the impact of different presidential terms on economic indicators. Moreover, a prediction is to be made using RandomForest for the next Inflation Rate of the country.


## Gathered Data / Dataset
- Dataset Type: Time-series data
- Dataset Size: 63 entries
- [Link to Inflation Dataset](https://fred.stlouisfed.org/series/FPCPITOTLZGPHL)
- [Link to Debt Dataset](https://statrealm.com/sector/economy/external-debt-stocks-total-dod-current-us/PHL)

## Tools and Libraries

- [Jupyter Notebook](https://jupyter.org)
- [Visual Studio Code](https://code.visualstudio.com)
- [Python](https://www.python.org)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org)

## Installation

To run the analysis locally, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/Giyanellow/Time-Series-Analysis-on-Philippine-Debt-and-Inflation
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Conclusion

This project can conclude that the Philippine Inflation Rate is generally fickle and with the prediction using Machine Learning; prediction data can be improved using a larger dataset. Continously, the prediction proves that the next few years of inflation for the Philippines will be consistent with the last 5 years with a slow and inclined rate.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
