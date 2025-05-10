# Credit Card Customer Segmentation Project

## Overview
This project implements a customer segmentation analysis using Python and the KMeans clustering algorithm on a credit card transactions dataset. The goal is to identify distinct customer groups based on transaction behavior and demographic details.

## Dataset
The dataset contains detailed records of credit card transactions, including:
- Transaction details (amount, timestamp, unique transaction number)
- Cardholder information (first name, last name, gender, date of birth, occupation, address)
- Geographical data (city, state, zip, latitude, longitude, population)
- Merchant information (location, category)
- Fraud indicators

## Methodology
- **Libraries Used**: Pandas, Matplotlib, Seaborn, NumPy, Scikit-learn, Folium
- **Steps**:
  1. Imported necessary libraries for data processing and visualization.
  2. Loaded and explored the credit card transactions dataset.
  3. Preprocessed data using StandardScaler and OneHotEncoder.
  4. Applied KMeans clustering to segment customers.
  5. Visualized results with maps and statistical summaries.

## Results
- **Cluster 0**: Younger customers (age 30-50), high transaction amounts, account for 30% of customers but 60% of total transaction value and orders.
- **Cluster 1**: Older customers with lower transaction values and frequency.

## Usage
1. Clone the repository.
2. Install required libraries: `pip install pandas matplotlib seaborn numpy scikit-learn folium`.
3. Run the Jupyter notebook `Credit Card Customer Segmentation.ipynb` with the dataset `credit_card_transactions.csv`.

## Contact
For questions or collaboration, please reach out via [your email] or [your LinkedIn].

## License
[Specify license, e.g., MIT]