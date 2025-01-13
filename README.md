# Customer Purchase Prediction with Personalized Recommendation

This project involves building a predictive model to analyze customer behavior and recommend products based on their characteristics and purchase history. By leveraging the dataset provided, the model aims to enhance customer engagement and improve conversion rates.

## Dataset Overview

The dataset contains 1,500 entries with the following 9 columns:

| Column               | Data Type | Description                                                                  |
| -------------------- | --------- | ---------------------------------------------------------------------------- |
| `Age`                | int64     | Age of the customer.                                                         |
| `Gender`             | int64     | Encoded gender (e.g., 0 = Female, 1 = Male).                                 |
| `AnnualIncome`       | float64   | Annual income of the customer (in currency units).                           |
| `NumberOfPurchases`  | int64     | Total number of purchases made by the customer.                              |
| `ProductCategory`    | int64     | Encoded category of products purchased (e.g., 0 = Electronics, 1 = Fashion). |
| `TimeSpentOnWebsite` | float64   | Time (in minutes) spent by the customer on the website.                      |
| `LoyaltyProgram`     | int64     | Whether the customer is part of the loyalty program (0 = No, 1 = Yes).       |
| `DiscountsAvailed`   | int64     | Number of discounts availed by the customer.                                 |
| `PurchaseStatus`     | int64     | Target variable (0 = No purchase, 1 = Purchase made).                        |

## Project Goals

1. **Predict Customer Purchases:**
   Develop a machine learning model to predict the likelihood of a customer making a purchase based on their profile and behavior.

2. **Personalized Recommendations:**
   Recommend product categories to customers by analyzing their purchase patterns and preferences.

3. **Insights for Marketing:**
   Provide actionable insights for personalized marketing strategies, such as targeting specific age groups or loyalty program members.

## Workflow

1. **Data Preprocessing:**

   - Handle missing values (if any).
   - Scale numerical features (`AnnualIncome`, `TimeSpentOnWebsite`).
   - Encode categorical variables (`Gender`, `ProductCategory`).

2. **Exploratory Data Analysis (EDA):**

   - Visualize purchase trends across different age groups, genders, and income levels.
   - Analyze the relationship between time spent on the website and purchase likelihood.

3. **Model Development:**

   - Train a classification model (e.g., Logistic Regression, Random Forest, SVM, Naive Bayes) to predict `PurchaseStatus`.
   - Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.

## Tools and Technologies

- **Programming Language:** Python
- **Libraries:**
  - Data Manipulation: pandas, numpy
  - Visualization: matplotlib, seaborn
  - Machine Learning: scikit-learn, xgboost
- **IDE:** Jupyter Notebook or any Python IDE

## Results and Deliverables

- A trained model capable of predicting customer purchase likelihood.
- A recommendation engine for suggesting products based on customer profiles.
- Visualizations and insights for better marketing strategies.

## How to Run the Project

1. **Install Dependencies:**

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
   ```

2. **Run the Script:**
   Execute the Python scripts provided in the repository to preprocess data, train models, and generate recommendations.

3. **View Results:**
   Check the generated output files and visualizations for model performance and recommendations.

##

## Contact

For further information or support, please contact:

- Name: Abinayashri S
- \*\*Email: \*\***[abinayashrigupta05@gmail.com](mailto:abinayashrigupta05@gmail.com)**

---
