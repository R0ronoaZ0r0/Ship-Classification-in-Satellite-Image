The Code was created and run in google drive.




To run the code you need to change the base file path at the top of each file to your file path.




First you run the “load_data” file which will create the dataset.




Then you run the “clustering” file which will extract the features of the data and cluster it.




Then you run “model_training” to train and test the dataset with the clusters. 




If you want to reoptimize the architecture of the model in the train file you can run the “genetic” file which will find the optimal architecture for a given clustering. Then you can manually adjust the architecture in the “model_training” file.


In our project, the initial custom CNN model was overwritten by the GA modified CNN. So the initial model is not present in the project file.