# Inflation and External Debt Analysis - Philippines

## Overview

This repository contains Python code for analyzing inflation and external debt data for the Philippines. The analysis involves importing, cleaning, and combining datasets related to inflation rates and external debt over several years. The primary goal is to explore the relationship between inflation and external debt, as well as to visualize trends and identify patterns.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Import](#data-import)
3. [Data Cleaning](#data-cleaning)
4. [Combining Datasets](#combining-datasets)
5. [Data Analysis](#data-analysis)
6. [Visualization](#visualization)
7. [Conclusion](#conclusion)

## Introduction

The analysis involves two main datasets:

- **Inflation Data**: This dataset contains the inflation rates for the Philippines over several years.
- **External Debt Data**: This dataset includes information about the total external debt stocks for the Philippines.

The primary objective is to combine these datasets, clean the data, and analyze the relationship between inflation and external debt. Additionally, the analysis includes identifying the impact of different presidential terms on economic indicators.

## Data Import

The code begins by importing the necessary libraries, including pandas, numpy, matplotlib, seaborn, and sklearn. It then reads the inflation and external debt datasets from CSV files.

```python
# Import Libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import os
import warnings
import sklearn

# ... (code for importing datasets)
