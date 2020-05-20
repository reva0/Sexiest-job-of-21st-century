# Sexiest job of 21st century
# Kaggle-Sexiest-Job-Competition

Final output / Target variable is to predict the common job role.

Over 15000 rows and 397 columns, I have selected the most important features like education, country, age, degree, major,industry, experience etc that are much correlated with the target variable(job role)

# Part I - Data Cleaning 
The biggest challenge was the data cleaning part as the data is taken from a survey. It has a lot of errors and NaN values which was replaced with 0 and columns with a lot of missing values were dropped as we already has 397 columns.

# Part II - Visulaization
The notebook has exploratory visual analysis. Tools like seaborn, matplotlib, plotly were used for multiple features inorder to have a better understanding about each extracted feature.

# Part III - Data Normalization

Normalization is a scaling technique in which values are shifted and rescaled to numeric values. It is also known as Min-Max scaling. This helps in model to understand the data
Data is then split into training and testing sets.

# Part IV - Training and testing
Model is split, and trained and tested using sklearn.

The results/accuracy is calculated. 
K-fold CV is also calculated to see how accuracy is changed.


# Result
Data science is the hot field. 
According to the Harvard Business Review in 2012, it’s The Sexiest Job of the 21st Century. 
