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
1.importig librarries that are required
2.read the dataset after uploading using pandas package
3.data preprocessing(check whether any missing values or normalization required in the features)
4.if we find then preprocess the data by required techniques and try to clean the data because it will helps us try to get better accuracy
5.here we filled with missing values in "total_bedrooms" using mean function
6.we converted the "ocean_proximity"(object) to numbers
7.using the multi linear regression algorithm for the cleaned data
8.using train test split function we split the data into train and test data 
9.evaluating using test data(i.e splitted from original data)
10.by using score function we can find the accuracy
11.we can improve the accuracy by taking the better features without correlation
