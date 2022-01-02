# tensorflow_325_bird_species

Build a CNN model to classify bird species. The training set consists of 47332 images of 325 different bird species. A validation set consisting of 1625 images (5 images for each bird specie) will be used to test the performance of the model and a final test set (1625 images) will be used to test the generalization performance of the model.

The data and the task comes from a Kaggle challenge: https://www.kaggle.com/gpiosenka/100-bird-species/version/48?select=valid

The training set has been used to train the model while the test set has been used to as the validation set.

Image augmentation has been used on the train set.

After training for 15 epochs a validation accuracy of around 71% has been obtained.

