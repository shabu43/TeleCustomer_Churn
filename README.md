
# Customer Churn Prediction and Segmentation

This project aims to predict customer churn for a telecom company and segment customers into distinct groups. The dataset includes customer demographics, service usage, and account information, which are used to build predictive models and perform clustering analysis. The objective is to improve customer retention strategies by identifying factors leading to churn and understanding customer segments.

## Features of the Project

### 1. Data Preprocessing
- **Handling Missing Values**: Imputed missing values where necessary.
- **Encoding Categorical Features**: Converted categorical features to numerical using `OneHotEncoder`.
- **Feature Scaling**: Scaled numerical features with `StandardScaler`.
- **Feature Engineering and Selection**: Used statistical methods like Chi-Square and ANOVA to identify significant features for churn prediction.

### 2. Feature Selection
- **Chi-Square Test**: Applied to categorical variables to assess their relevance in predicting churn.
- **ANOVA (Analysis of Variance)**: Used for numerical features to determine their contribution to churn.
- **Feature Elimination**: Removed statistically insignificant features to improve model accuracy and efficiency.

### 3. Models
- **Supervised Learning Algorithms**:
  - **Logistic Regression** with regularization techniques (Lasso, Ridge, ElasticNet)
  - **Decision Tree Classifier**
  - **Random Forest Classifier**
  - **Support Vector Machine (SVM)**
- **Feature Selection**: Used Recursive Feature Elimination (RFE) to further enhance model accuracy by identifying essential features.

### 4. Customer Segmentation 
- **K-Means Clustering**: Segmented customers based on tenure, monthly charges, and total charges.
- **Optimal Cluster Selection**: Used the **Elbow Method** to determine the optimal number of clusters.
- **Cluster Analysis**: Summarized key feature averages for each cluster and calculated churn rates within each cluster, offering insights into different customer segments and their likelihood to churn.

### 5. Model Evaluation
- **Evaluation Metrics**: Assessed model performance using accuracy, classification reports, and cross-validation for reliability.
- **Hyperparameter Tuning**: Used GridSearchCV to optimize model parameters for better performance.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`

Install the necessary packages using:
```bash
pip install -r requirements.txt
```

### Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Customer-Churn-Prediction.git
   ```
2. Open the notebook:
   ```bash
   jupyter notebook TeleCustomer.ipynb
   ```
3. Run all cells to preprocess data, train models, and perform customer segmentation.

## Results and Insights
- **Churn Prediction**: Key features contributing to churn include monthly charges and tenure.
- **Customer Segmentation**: K-Means clustering identified distinct customer segments based on spending and tenure, with each segment showing different churn probabilities. These insights enable targeted retention strategies.

## Contributing
Contributions are welcome!

---

