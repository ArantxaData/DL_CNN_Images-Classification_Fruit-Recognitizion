# DL_CNN_Images-Classification_Fruit-Recognitizion
Convolutional neural network for classifying fruits
This kernel tries to compare several methods for performing a classification of fruits images.
There are theee approaches considered:
   1. In the first one we define a custom convolutional neural network for this task.
   2. The second one tries to perform the classification comparing the performance of several pre-trained models. For this purpose VGG16 seems to perform slightly better than the other ones, so we consider also fine-tuning with this model for comparison and demonstrative purposes.
   3. The third approach is also taken VGG16 model as baseline, and performs a hyperparameter tuning so that we can finally compare the optimized model with the initial custom model of the first approach.

For doing this, we have a train dataset of 41322 images of fruits belonging to 81 different classes, and a validation set with 6942 images and a final test set with 6935 images.
