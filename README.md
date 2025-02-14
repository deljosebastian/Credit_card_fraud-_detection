# Credit Card Fraud Prediction Analysis

Comprehensive analysis of credit card default prediction using machine learning techniques.

## 📁 Dataset
**Default of Credit Card Clients Dataset**  
- Contains 30,000 samples with 25 features
- Features include demographic information, payment history, credit statements, and payment amounts
- Target variable: `default payment next month` (binary classification)

Key Features:
- `LIMIT_BAL`: Credit limit
- `PAY_0-PAY_6`: Payment history status
- `BILL_AMT1-BILL_AMT6`: Bill statement amounts
- `PAY_AMT1-PAY_AMT6`: Previous payment amounts
- Demographic features: Sex, Education, Marriage Status, Age

## 🔍 Analysis Overview

### Key Steps:
1. **Data Loading & Initial Exploration**
   - Check basic statistics and data structure
   - Verify null values and duplicates
   - Rename columns for better readability

2. **Data Preprocessing**
   - Handle outliers using Interquartile Range (IQR) method
   - Separate numerical features
   - Visualize distributions with boxplots

3. **Feature Engineering**
   - Temporal feature renaming (e.g., `PAY_0` → `sept_paystat`)
   - Column standardization for clarity

### Key Observations:
- No missing values detected
- Zero duplicate records
- Significant outliers in financial features handled with IQR
- A class imbalance in the target variable


