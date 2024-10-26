To run this project successfully, you can follow these step-by-step instructions:

---

# Loan Prediction Model

This project builds a loan approval prediction model using logistic regression. The dataset is processed, and a logistic regression model is trained and tested for accuracy.

## Dataset
The dataset (`train_ctrUa4K.csv`) contains features related to loan applicants, such as `ApplicantIncome`, `LoanAmount`, and `Credit_History`, with `Loan_Status` as the target variable indicating loan approval (1 for approved, 0 for not approved).

## Project Setup

### Requirements
Ensure you have Python and the required packages installed:

```bash
pip install pandas scikit-learn
```

### Steps to Run the Project
1. **Clone the Repository** (or download the project files):
    ```bash
    git clone https://github.com/samabaso/data-science.git
    cd data-science
    ```

2. **Place the Dataset**:
   Ensure `train_ctrUa4K.csv` is in the same directory as the Python script.

3. **Run the Script**:
   Run the Python script with the following command:
   ```bash
   python loan_prediction.py
   ```

## Code Breakdown

The project code in `loan_prediction.py`:

1. **Data Preprocessing**:
   - Load the data, encode the target variable, and drop missing values.

2. **Train-Test Split**:
   - Split data into 80% training and 20% testing.

3. **Feature Encoding**:
   - Encode categorical features using one-hot encoding.

4. **Train the Model**:
   - Use logistic regression to train the model.

5. **Evaluate the Model**:
   - Predict on test data and print the accuracy score.

## Expected Output

Upon running, the script will display:
- Predicted values for test data.
- Model accuracy score.

```plaintext
Predicted Values on Test Data: [1 0 1 ... 0 1 1]
Accuracy Score on Test Data: 0.81
```

Adjust the model and data as needed to improve performance or to test new features.

---
