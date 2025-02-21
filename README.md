## Customer Churn Prediction

This project aims to predict customer churn using machine learning techniques. The dataset contains customer-related information, and the goal is to analyze key features contributing to customer retention and churn.

### 📂 Project Structure
```
📦 CustomerChurn
 ┣ 📜 CustomerChurnPrediction.ipynb  # Jupyter Notebook for model development
 ┣ 📜 README.md                       # Project documentation
 ┣ 📜 dataset.csv                      # Dataset used for analysis
 ┣ 📜 requirements.txt                 # Required dependencies
 
```

### 📊 Dataset
- The dataset consists of customer information and churn labels.
- Features include customer demographics, usage behavior, and subscription details.
- The target variable is whether a customer churned (Yes/No).

### 🚀 Features & Methodology
1. **Data Preprocessing**
   - Handling missing values
   - Feature engineering
   - Encoding categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Identifying key patterns in customer behavior
   - Visualization of churn trends

3. **Modeling & Evaluation**
   - Implemented machine learning models such as:
     - Logistic Regression
     - Decision Trees
     - Random Forest
     - Support Vector Machines (SVM)
   - Evaluated models using accuracy, precision, recall, and F1-score.

### 🛠 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Preethamgm/CustomerChurn.git
   cd CustomerChurn
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook CustomerChurnPrediction.ipynb
   ```

### 📈 Results
- The best-performing model achieved an accuracy of **85%** 
- Feature importance analysis revealed that **customer engagement data** was the most critical factor in customer churn.

### 🤝 Contributing
Feel free to fork this repository and contribute by submitting pull requests. Suggestions and feedback are welcome!

### 📜 License
This project is licensed under the **MIT License**.
