# KNN-binary-classification
A KNN binary classifier in python, part of my introduction to machine learning collegial course.

Given the MAGIC gamma telescope dataset. This dataset is generated to simulate registration of high energy gamma particles in a ground-based atmospheric Cherenkov gamma telescope using the imaging technique. The dataset consists of two classes: gammas (signal) and hadrons (background). There are 12332 gamma events and 6688 hadron events.

### What the provided code does:
1. The dataset is class imbalanced. To balance the dataset, we randomly put aside the extra readings for the gamma “g” class to make both classes equal in size.

2. We split the dataset randomly so that the training set would form 70% of the validation set 15% and 15% for the testing set.

3. We apply K-NN Classifier to the data.

4. We apply different k values to get the best results.

5. Tables are made of all trained models' accuracy, precision, recall and f-score as well as confusion matrix.
