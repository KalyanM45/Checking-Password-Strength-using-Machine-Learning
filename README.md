# Checking-Password-Strength-using-Machine-Learning
 
This is a Python code for building a machine learning model to predict the strength of passwords based on their character-level features. The model is trained on a dataset of passwords labeled as weak, medium, or strong and uses logistic regression and gradient boosting algorithms for classification.

# Dataset

The dataset used for training the model is stored in the "Password Strength.csv" file and contains a list of passwords along with their corresponding strength category. The dataset is preprocessed by dropping the rows with missing values and visualizing the distribution of the password strength categories. Let the features be

Password - 670k unique values for password collected online

Strength - three values(0 , 1 , 2) i.e. 0 for weak, 1 for medium, 2 for strong.

Strength of the password based on rules(such as containing digits, special symbols , etc.)

# Feature Engineering
To convert the password strings into machine-readable features, we use the TF-IDF vectorizer at the character level. This converts each password into a vector of numerical features that capture the importance of each character in the password.

# Model Training and Evaluation
We split the dataset into training and testing sets and train two models, logistic regression and gradient boosting, on the training set. We evaluate the performance of the models on the testing set using metrics such as accuracy, precision, recall, and F1-score.

# Usage
To use the password strength prediction model, simply run the Python code and input a password when prompted. The model will preprocess the password using the same vectorizer used for training the model and predict its strength category.

# Dependencies
The code requires the following Python libraries to be installed:

Pandas

numpy

Seaborn

Sklearn
# Acknowledgements
This project was inspired by the Kaggle dataset on password strength and the corresponding competition. We also acknowledge the open-source Python libraries used in this project and their contributors.
