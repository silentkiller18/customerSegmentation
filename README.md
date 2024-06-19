# Customer Segmentation Analysis

This repository contains code for analyzing customer segmentation using K-means clustering on Mall Customers dataset.

## Files

- `customer_segmentation.ipynb`: Jupyter notebook containing the analysis code.
- `Mall_Customers.csv`: Dataset used for analysis.

## Overview

The analysis includes data cleaning, exploratory data analysis (EDA), and clustering of customers based on their demographic and spending behavior.

### Data Cleaning and Renaming

- Renamed column 'Genre' to 'Gender'.
- Dropped 'CustomerID' column as it was not necessary for analysis.

### Exploratory Data Analysis (EDA)

#### Histograms
- Plotted histograms for Age, Annual Income, and Spending Score.
- Used seaborn's `histplot` with `kde=True` for density plot overlay.

#### Gender Distribution
- Count plot of Gender distribution among customers.

#### Age Distribution
- Bar plot showing the number of customers in different age groups.

#### Spending Score Distribution
- Bar plot showing the number of customers in different spending score ranges.

### Clustering

#### Clustering Based on Age and Spending Score

- Applied K-means clustering to group customers based on Age and Spending Score.
- Plotted clusters on a scatter plot.

#### Clustering Based on Annual Income and Spending Score

- Applied K-means clustering to group customers based on Annual Income and Spending Score.
- Plotted clusters on a scatter plot.

#### 3D Visualization

- Visualized clusters of customers in 3D space using Age, Annual Income, and Spending Score.

## Requirements

- Python 3.x
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn

## Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-segmentation.git
   cd customer-segmentation

2.Install required libraries:
```
pip install -r requirements.txt
```

3. Run the Jupyter notebook customer_segmentation.ipynb to see the analysis.

## Results
The clustering results show distinct groups of customers based on their spending behavior and demographic characteristics.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
