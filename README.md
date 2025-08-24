# ML_miniproject_IRISdataset
A mini project using Machine Learning concepts based on the topic of :

    IRIS Flower Classification using ScikitLearn and other python concepts

Step 1- Import Libraries

  We load the tools we need:
  
    pandas → handles tabular data (like Excel).
    
    seaborn & matplotlib → for pretty charts.
    
    sklearn → machine learning library (has datasets + algorithms).

Step 2-Load Dataset

We use the Iris dataset — a very famous dataset in ML.

It contains 150 flowers (rows).

  Each flower has 4 features (columns):

    sepal length
    
    sepal width
    
    petal length
    
    petal width
  
  Each flower belongs to 1 of 3 species:
  
    Setosa 🌱
    
    Versicolor 🌿
    
    Virginica 🌸


Step 3-Exploratory Data Analysis (EDA)

  We do visualization to understand the dataset:
  
    Pairplot → compares every feature against each other to see patterns.
    
    Heatmap → shows correlations (relationships between features).


Step 4-rain-Test Split

  We split our dataset into 2 parts:
    
    Training data (80%) → used to teach the model.
  
    Testing data (20%) → used to check if the model really learned or is just memorizing.

Step 5-Train Models

  We try 3 different ML algorithms:
    
    Logistic Regression → good for simple problems.
    
    Decision Tree → like a flowchart that asks yes/no questions.
    
    Random Forest → combines many decision trees for better accuracy.
    
Step 6-Evaluate Models

  We test the models on unseen test data.
  
    Classification report shows:
    
      Precision → How many predicted positives were actually positive?
      
      Recall → How many actual positives did we catch?
      
      F1-score → Balance of precision and recall.
      
      Accuracy → Overall correct predictions.
    
    Confusion Matrix → a table that shows actual vs predicted species. (Example: 10 flowers were setosa, model got all 10 correct.)

Thus building an Machine Learning Model that predicts a flowers species just from its measurements
