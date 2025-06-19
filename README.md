# Loan Prediction using Logistic Regression

This project uses logistic regression to predict whether a loan will be approved or not based on customer data. It is a basic machine learning classification task using a supervised learning algorithm.

## Project Structure

- `logistic_regression_loan_prediction.ipynb`: Main Jupyter Notebook containing data preprocessing, model training, and prediction steps.
- `data/`: Contains the dataset used.
- `requirements.txt`: List of required Python libraries.
- `README.md`: Project documentation.

## Features

- Cleaned and preprocessed raw loan data
- Handled missing values and categorical features
- Trained a logistic regression model for binary classification (Loan Approved or Not)
- Evaluated model performance
- Made predictions on test data

## Tools & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## How to Use

1. **Clone the repository:**

```bash
git clone https://github.com/nurulashraf/logistic-regression-loan-prediction.git
cd logistic-regression-loan-prediction
````

2. **Create a virtual environment (optional but recommended):**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

4. **Run the Jupyter Notebook:**

```bash
jupyter notebook
```

Open `logistic_regression_loan_prediction.ipynb` to explore the code, train the model, and make predictions.

## License

This project is licensed under the [MIT License](LICENSE).
