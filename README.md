Fake news Detection
Importing required library
Inserting fake and real dataset
Inserting a column called "class" for fake and real news dataset to categories fake and true news. 
Removing last 10 rows from both the dataset, for manual testing 
Merging the manual testing dataframe in single dataset and save it in a csv file.
Merging the main fake and true dataframe
"title",  "subject" and "date" columns is not required for detecting the fake news, so I am going to drop the columns.
Randomly shuffling the dataframe
Creating a function to convert the text in lowercase, remove the extra space, special chr., ulr and links.
Defining dependent and independent variable as x and y
Splitting the dataset into training set and testing set.
Convert text to vectors
used models:
### 1. Logistic Regression
### 2. Decision Tree Classification
### 3. Gradient Boosting Classifier
### 4. Random Forest Classifier
Model Testing With Manual Entry
News:
Result : fake news or Real news with having prediction : ### LR,DT,GBC,RFC

                                    "Stay informed, fight misinformation, and keep learning!"🚀
