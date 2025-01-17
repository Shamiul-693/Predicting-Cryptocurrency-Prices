# Leveraging Random Forest, Regression, and KNN for Predicting Cryptocurrency Prices

This repository contains a machine learning project focused on predicting cryptocurrency prices using various algorithms, including Random Forest, Linear Regression, and K-Nearest Neighbors (KNN).

## Dataset

The dataset used in this project consists of historical cryptocurrency price data and is provided in a CSV format. You can download the dataset directly from this repository.

### Download the Dataset

To download the dataset, follow these steps:

1. **From GitHub Website**:
   - Go to the `datasets` directory in this repository.
   - Click on the dataset CSV file (e.g., `bitcoin.csv`).
   - Click on the dataset CSV file (e.g., `ethereum.csv`).
   - Once the file opens, click on the "Download" button (or right-click on "Raw" and choose "Save Link As...") to save the file to your local machine.


### Example Code to Load the Dataset

You can load the CSV dataset into your Python script using **pandas** as shown below:

```python
import pandas as pd

# Load the dataset
df_bitcoin = pd.read_csv('datasets/Bitcoin.csv')
df_eth = pd.read_csv('datasets/ethereum.csv')
# Display the first few rows of the dataset
print(df.head())
