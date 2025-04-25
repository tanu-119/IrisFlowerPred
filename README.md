IRIS Flower Classification:
      This project uses the famous IRIS dataset to classify flower species based on their physical characteristics. Multiple machine learning models are trained and evaluated to find the 
      most accurate one.

Dataset:
  The dataset contains 150 rows with 4 features and 1 target column:
    Features:
    sepal_length
    sepal_width
    petal_length
    petal_width

Target: species (Setosa, Versicolor, Virginica)

Technologies Used:
  Python
  Pandas
  Scikit-learn

Steps Performed:
    1. Load the Dataset
    Read the dataset from a CSV file using pandas.
    2. Handle Missing Values
    Numeric columns: Filled using mean.
    Categorical target column: Filled using mode.
    3. Data Splitting
    The data is split into training and testing sets (80/20 split).
    4. Feature Scaling
    Used StandardScaler to normalize features for better model performance.
    5. Models Used
    The following models are trained and evaluated:
        Logistic Regression
        K-Nearest Neighbors (KNN)
        Support Vector Machine (SVM)
        Random Forest
        Decision Tree
        Naive Bayes
    6. Evaluation
    Each model is evaluated using accuracy score on test data.
    7. Prediction
    The trained Random Forest model is used to predict the species for new flower measurements.

How to Run:
    Upload IRIS.csv into your working directory.
    Open the notebook or script.
    Install dependencies (if needed):
         pip install pandas scikit-learn
Run the code and check the output.

