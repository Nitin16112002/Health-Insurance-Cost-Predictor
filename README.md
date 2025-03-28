# Health Insurance Cost Predictor

## 📌 Overview
This project aims to predict health insurance costs based on various factors such as age, BMI, smoking status, and region. We utilize **regularized regression techniques** (Ridge, Lasso, and ElasticNet) to enhance predictive performance while preventing overfitting.

## 📊 Dataset
The dataset contains information about individuals, including:
- **age**: Age of the policyholder
- **sex**: Gender (Male/Female)
- **bmi**: Body Mass Index
- **children**: Number of dependents
- **smoker**: Smoking status (Yes/No)
- **region**: Geographical location
- **charges**: Medical insurance cost (Target variable)

## 🛠️ Technologies Used
- **Python**
- **Pandas & NumPy** (Data manipulation)
- **Matplotlib & Seaborn** (Data visualization)
- **Scikit-Learn** (Machine Learning models)

## 🏆 Models & Performance

| Model      | Train R² Score | CV Score | Test R² Score |
|------------|---------------|----------|--------------|
| **Ridge Regression** | 0.7594 | 0.7535 | 0.7009 |
| **Lasso Regression** | 0.7649 | 0.7603 | 0.6846 |
| **ElasticNet Regression** | 0.7594 | 0.7535 | 0.7007 |

### Key Observations:
- **Ridge & ElasticNet** performed similarly, balancing bias and variance effectively.
- **Lasso Regression** had a slightly higher training score but lower test accuracy, indicating possible underfitting.
- The **ElasticNet model** provided a good trade-off by combining L1 (Lasso) and L2 (Ridge) regularization.


## 🚀 How to Run the Project
1. Clone the repository:  
   ```sh
   git clone https://github.com/your-username/Health-Insurance-Cost-Predictor.git
