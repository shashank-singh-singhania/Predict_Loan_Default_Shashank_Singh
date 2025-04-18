# Predicting Loan Default

This project classifies whether a borrower will default on a loan based on their financial history and credit attributes using a **Random Forest Classifier**.

---

## 📊 Dataset

The dataset includes borrower information with various financial and personal attributes. The goal is to predict the binary target column `Default` (1 = Defaulted, 0 = No Default).

### Columns include:
- `Age`: Age of the borrower  
- `Income`: Annual income  
- `LoanAmount`: Amount of loan requested  
- `CreditScore`: Credit score value  
- `Education`: Education level  
- `EmploymentType`: Type of employment  
- `MaritalStatus`: Marital status  
- `HasMortgage`: Whether borrower has a mortgage  
- `HasDependents`: Presence of dependents  
- `LoanPurpose`: Purpose of the loan  
- `HasCoSigner`: Whether the loan has a co-signer  
- `Default`: **Target column** (1 = defaulted, 0 = not defaulted)

---

## 🧠 Features

- **Data Preprocessing**:
  - Label encoding of categorical features
  - Feature scaling using StandardScaler
  - Train-test split (80-20)
  
- **Machine Learning Model**:
  - Model used: `RandomForestClassifier`
  - Performance evaluated using Accuracy, Precision, Recall, and F1 Score

- **Visualization**:
  - Confusion matrix heatmap for understanding predictions

---

## ⚙️ Installation & Usage

Run the Jupyter Notebook in **Google Colab**:

1. Clone this repository or download the `.ipynb` file  
2. Open Google Colab and upload the notebook `Loan_Default_Prediction.ipynb`  
3. Upload the dataset file `Predict loan default data set.xlsx` when prompted  
4. Run all cells to train the model and view results

---

## 📈 Results

Sample evaluation metrics (varies depending on data):

