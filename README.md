# Customer Churn Prediction

## Overview

This project aims to predict customer churn using various machine learning techniques. The dataset used for this project is sourced from Kaggle, and it contains customer information from a bank. The objective is to analyze customer data and build a predictive model to determine whether a customer will exit the bank.

## Author

- **Name**: Swayam Massey
- **GitHub**: [swayammassey](https://github.com/swayammassey)

## Project Structure

```
customer-churn-prediction/
├── data/
│   ├── raw/                     # Contains the raw dataset
│   │   └── Churn_Modelling.csv
│   └── processed/               # Contains the processed dataset
│       └── processed_churn_data.csv
├── notebooks/                   # Jupyter notebooks for analysis and modeling
│   └── customer_churn_analysis.ipynb
├── requirements.txt             # Python dependencies
├── README.md                    # Project documentation
└── .gitignore                   # Files and directories to be ignored by Git
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/swayammassey/customer-churn-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd customer-churn-prediction
   ```
3. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # For macOS/Linux
   venv\Scripts\activate     # For Windows
   ```
4. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

- Open Jupyter Notebook in the `notebooks` folder:
   ```bash
   jupyter notebook
   ```
- Run the `customer_churn_analysis.ipynb` notebook to perform data analysis and model building.

## Conclusion

This project demonstrates the process of customer churn prediction, including data preprocessing, model training, and evaluation. The insights gained can help businesses understand customer behavior and implement strategies to reduce churn.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
