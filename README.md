# Exporting-a-train-model
When you attain the desired accuracy of a model the next question is how to use it later as a trained model.
We use SVM(suport vector machine) to train the model on ECG images which contains images of normal and abnormal patients.
The first part of the code is to read the images from two folders(can be many depending on data) present in the root folder.
We give the same size to all the images and store them in the list as features of the data.
# Feature engineering
Labels of the data is two folders named as normal and abnormal.
The next step was to split the data into train and test sets to see validation of the model.
In the next two parts of the code, we convert the data into a NumPy array to reshape the data so that model can be fit on it.
After that model do the traing on the assigined data and gives its prediction.
# Validation of model
The final step is to checke the accuracy of the model and we are ready to deploy it.
In order to deploy it we need to export or save the model when it gives best performance.
# Exporting the model
So, in the last part of code we export the model and save it in a file to use it later.
