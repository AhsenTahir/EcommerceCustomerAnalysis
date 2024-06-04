# EcommerceCustomerAnalysis

## Description

This project contains an analysis of customer behavior and spending patterns based on the Ecommerce Customers dataset. The dataset includes information about customers who buy clothes online and offers insights into their session lengths, time spent on the app and website, and yearly amount spent.

## Dataset

The dataset contains 500 entries with the following columns:

- `Email`: Customer's email address
- `Address`: Customer's address
- `Avatar`: Customer's avatar
- `Avg. Session Length`: Average session length of a customer
- `Time on App`: Time spent on the mobile app by the customer
- `Time on Website`: Time spent on the website by the customer
- `Length of Membership`: Length of the customer's membership
- `Yearly Amount Spent`: Yearly amount spent by the customer

## Files

- `data/EcommerceCustomers.csv`: The dataset used for analysis.
- `notebooks/EcommerceCustomerAnalysis.ipynb`: Jupyter Notebook containing the data analysis and visualizations.

## Analysis

The analysis focuses on understanding customer behavior to help the company decide whether to focus their efforts on their mobile app experience or their website. Key aspects of the analysis include:

- Descriptive statistics of the dataset.
- Correlation analysis between different features.
- Visualizations to identify trends and patterns.
- Regression analysis to predict the yearly amount spent based on other features.

## Installation

To run the analysis, you need to have Python installed along with the following packages:

- pandas
- matplotlib
- seaborn
- scikit-learn
- jupyter

You can install the necessary packages using pip:

```sh
pip install pandas matplotlib seaborn scikit-learn jupyter

Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or suggestions.
