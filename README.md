# Houseprice_Machinelearning-_project-
#Steps to follow
1.load the dataset
2.read the dataset
3.data preprocessing
4.choosing the model
5.training the model
6.evaluate the model
7.update the model by changing hyperparameters to get better accuracy

#Approach
1.importig librarries
2.read the dataset after uploading using pandas
3.data preprocessing(check whether any missing values,normalization and some other techniques to get better accuracy)
4.here we filled with missing values in "total_bedrooms" using mean function
5.we converted the "ocean_proximity"(object) to numbers
6.using the linear regression algorithm for the cleaned data
7.using train test split function we split the data into train and test data 
8.evaluating using test data(i.e splitted from original data)
9.by using score function we can find the accuracy
10.we can improve the accuracy by taking the better features without correlation
