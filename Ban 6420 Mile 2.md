 Cancer Dataset PCA and Logistic Regression

 Description
This project performs Principal Component Analysis (PCA) on the breast cancer dataset to identify essential variables for further analysis. Additionally, logistic regression is used to predict cancer outcomes based on the reduced dataset.

 Requirements
- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-learn

Steps Involved
1. Data Loading and Preprocessing
Load the Breast Cancer Dataset from sklearn.datasets.
Convert the dataset into a pandas DataFrame for easier manipulation.
The target variable indicates whether the cancer is malignant or benign.
2. Data Standardization
Standardize the features using StandardScaler to ensure all features have a mean of 0 and standard deviation of 1, which is necessary for PCA.
3. Principal Component Analysis (PCA)
Apply PCA to reduce the dimensionality of the dataset to 2 components.
The first two principal components capture the most variance in the dataset.
The explained variance ratio helps understand how much information is retained after reduction.
4. Visualization
Plot the reduced data in a 2D scatter plot, where the data points are color-coded based on the cancer diagnosis (malignant or benign).
5. Logistic Regression (Optional)
Train a Logistic Regression model on the PCA-reduced data.
Evaluate the model's performance using accuracy and a classification report.
