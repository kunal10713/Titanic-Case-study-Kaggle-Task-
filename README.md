# Titanic-Case-study-Kaggle-Task-

## Data Description:
### Overview:
The data has been split into two groups:

  1. training set (train.csv).
  2. test set (test.csv).
  
The training set is used to build your machine learning models. For the training set, outcome is provided (also known as the “ground truth”) for each passenger. Model will be based on “features” like passengers’ gender and class.
The test set is used to see how well your model performs on unseen data. For the test set, there is no ground truth for each passenger. It is ousr job to predict these outcomes. For each passenger in the test set, use will be the model we trained to predict whether or not they survived the sinking of the Titanic.

## Variable Notes:
**pclass**: A proxy for socio-economic status (SES)
  **1st** = Upper
  **2nd** = Middle
  **3rd** = Lower

**age**: Age of people.

**sibsp**: The dataset defines family relations in this way.
  **Sibling** = brother, sister, stepbrother, stepsister.
  **Spouse** = husband, wife (mistresses and fiancés were ignored).

**parch**: The dataset defines family relations in this way.
  **parent** = mother, father.
  **Child** = daughter, son, stepdaughter, stepson.
  Some children travelled only with a nanny, therefore parch=0 for them.
  
  ### Task: Predicting survival on the Titanic 
