# Disease Prediction System

## Description : 
Hello, this is a Disease Prediction System throught which you will be able to predict multiple diseases by giving a certain set of inputs.
You can also use this system as a web app for a better GUI experience.
The models which we have used gives a pretty accurate results on all the datasets that we have used.

## How to run the project

### Using Web App :
* You can visit this website and select the disease that you want to predict.
* Then give input to all the datafields and then click on the test results button
* The result box will give you the output by prediciting that whether a person have that disease or not.

### Using Python Code : 
* Clone this repository to your system
* Run the .ipynb file of the particular disease that you want to predict in jupyter notebook or google colab.
* Give your input in the custom data list and then run the file.
* Get output about whether a person has the disease or not.

## About the dataset :
We have used 4 different datasets for predicting 4 different diseases.
The four datasets are the following :
* Heart Dataset : https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset
* Diabetes Dataset : https://www.kaggle.com/datasets/mathchi/diabetes-data-set
* Chronic Kidney Disease Dataset : https://www.kaggle.com/datasets/mansoordaku/ckdisease
* Breast Cancer Dataset : https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

These datasets have large amount of data so that we can get good accuracy score using different models.


## Steps followed :
### Importing the libraries :
* pandas 
* numpy
* matplotlib
* seaborn
* sklearn


### Loading the dataset.

### Preprocessing the data :
* We cleaned the data by removing the irrelevant features.
* Removed null values.
* Splitted the dataset using in train and test form using train test split.
* For KNN model we transformed the dataset into Standart Scaler form to get a better output.

### Data Visualization : 
* Used matplotlib to seaborn to visualize the data
* By visualizing the data we got to know which features play the most important role in deciding the output of the model.
* Analyzed people of which gender or category are more likely to be affected by the disease.

### Using Models : 
We used the following models for predicting the data.
* Decision Tree
* KNN(K Nearest Neighbors)
* Logistic Regression

### Predicting the data :
* We predictied the model on X_train and then tested it on Y_test.
* We also gave custom input to the model and it prediciting with a good accuracy.

### Comparing the accuracy of the algorithms : 
We compared the accuracy of the 3 algorithms and found the model which gives the best accuracy.It helped us to choose the best model for our web app.


## Credits :
### Anushka Mahajan :
* Worked on Heart Disease Prediction and Breast Cancer Disease Prediction.
* Used Decision Tree Model and Logistic Regression.
* Contributed in PPT and Web App.

### Dwij Joshi :
* Worked on Diabetes Prediction and Chronic Kidney Disease Prediction.
* Used KNN and Logistic Regression.
* Contributed in PPT and Web App.





