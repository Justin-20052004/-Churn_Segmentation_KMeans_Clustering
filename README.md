# K-Means Customer Segmentation Using Churn Dataset

This project demonstrates the implementation of K-Means clustering to perform unsupervised customer segmentation using a churn-related dataset. The churn label and other irrelevant columns are removed, and clustering is applied only on numerical features.

## Objective

To group customers into similar segments using K-Means clustering (k=4) based on their behavioral and financial attributes.

## Dataset

Churn prediction dataset containing customer information such as:

- Credit Score  
- Age  
- Tenure  
- Balance  
- Number of Products  
- Estimated Salary  

Target labels and categorical columns were removed before clustering.

## Methodology

1. Load dataset using Pandas  
2. Drop unwanted columns (ID, names, churn label)  
3. Select numerical features  
4. Handle missing values  
5. Apply feature scaling using StandardScaler  
6. Perform K-Means clustering with k=4  
7. Visualize clusters using scatter plot  

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook  

## Output

- Cluster labels added to dataset  
- Scatter plot visualization of customer clusters  
- Segmented customer groups  

## How to Run

1. Clone the repository
2. Install required libraries
3. Open the Jupyter notebook
4. Run all cells

## Conclusion

K-Means clustering successfully segments customers into four distinct groups, helping understand customer behavior patterns. This approach can assist businesses in targeted marketing and retention strategies.

---

Author: Justin Raj S
