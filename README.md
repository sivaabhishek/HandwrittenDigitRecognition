# HandwrittenDigitRecognition

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/sivaabhishek/HandwrittenDigitRecognition/blob/master/LICENSE)

Handwritten digit recognition is an important filed of Optical Character Recognition
(OCR) and can be seen as a sub problem of OCR. It is the ability of a computer to
receive and interpret intelligible handwritten digit input from sources such as
documents, image and other devices. 


## MNIST DATASET

The MNIST database (Modified National Institute of Standards and Technology database) of handwritten digits consists of a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. Additionally, the black and white images from NIST were size-normalized and centered to fit into a 28x28 pixel bounding box and anti-aliased, which introduced grayscale levels.


## Support Vector Machines Usage

Support Vector Machines (SVM) were introduced as a machine learning method by
Cortes and Vapnik (1995). SVM is a binary classifier. Thus, the aim of SVM is
to find the best classification function to distinguish between members of the two
classes in the training data. In the case of classification, an SVM constructs an optimal separating hyperplane
in a high-dimensional feature space. The computation of this hyperplane relies on the
maximization of the margin and also the SVM is the best classifier among all the classifiers like the KNN, neural networks etc to detect the hand written digits.

## Usage

1. First run the generateClassifier.py file so that it will generate the classifier pickle file.
2. Next run the pp.py file and draw the numbers and then save the file.
3. Finally run the performRecognition.py file and see the output.

## Example

### Input 
![](https://github.com/sivaabhishek/HandwrittenDigitRecognition/blob/master/image.jpg)

### Output
![](https://github.com/sivaabhishek/HandwrittenDigitRecognition/blob/master/OUTPUT.jpg)
