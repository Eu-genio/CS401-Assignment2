# CS401-Assignment2
Hi Barak, the explanation of the code is in the code itself (Classifiers.ipynb), if run in jupyter notebook some headings and an easy to read format exists, with visual representation of some of the data. As stated in the assignment description i have not added test-i and train-io in this github

Imports needed: numpy, sklearn,keras,torch, seaborn and pandas.

For the algorithm itself it uses 2 hidden layers and a sigmoid function. 
The code then creates a model with an epoch of 400 and a batch size of 10, after epochs are over it creates a file called model2.h5 which stores it, which will then be used to create test-o
As for test-o, i have made it so everytime you run the code it creates a file text-o.txt with an updated version of the output given by the most recent model 
I also implemented a confusion matrix of the training set. (I could have implemented a function where the test set was used to create the confusion matrix, but i thought this would be more useful for training only)
I had used seaborn to represent more data regarding different models however those were previous versions and did not seem necessary to show. 
The output i got which was a 72 acc, was the highest i got with my machine without it taking half a day to process it. 
