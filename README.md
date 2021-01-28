# End to end Multi-Class Dog Breed Classification
This notebook builds an end-to-end multi-class image classifier, using Tensorflow 2.0 and Tensorflow Hub.

1. Problem
Identifying the breed of a dog given an image of a dog.

2. Data
The data we're using is from Kaggle's dog breed identification competition.

https://www.kaggle.com/c/dog-breed-identification/data

3. Evaluation
The evaluation is a file with prediction probabilities for each dog breed of each test image

4. Features
Some information about the data:

We're dealing with images (unstructured data) so it's best we used deep learning/transfer learning
There are 120 breeds of dogs (this means there are 120 different classes)
There are around 10,000+ images in the training set (with labels)
There are around 10,000+ images in the test set (no labels)
