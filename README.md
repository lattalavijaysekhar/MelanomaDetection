# Melanoma Cancer Detection Using CNN
Melanoma is a type of skin cancer that develops from melanocytes, the cells responsible for producing melanin, the pigment that gives skin its color. It is one of the most dangerous forms of skin cancer because it can grow rapidly and spread (metastasize) to other parts of the body if not detected and treated early.

Melanoma cancer detection using Convolutional Neural Networks (CNNs) is an application of deep learning techniques for diagnosing skin cancer from images. CNNs are particularly effective for image classification tasks because they automatically learn spatial hierarchies of features from raw pixel inputs, which is crucial for medical imaging tasks like melanoma detection.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

## General Information

### Problem Statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Conclusions
- Conclusion 1: Model 1 Training Accuracy 62.10% and Validation Accuracy 53.91% are closely same, but very low which indicates that the model is underfitting.
- Conclusion 2: Model 2 on Augmented Data Training Accuracy 51.95% and Validation Accuracy 50.78% are relatively close, and the losses are also somewhat close. But both accuracy values are low. Model likely needs more epochs to train with class imbalance handled.
- Conclusion 3: Model 3 on rectified class imbalance data Training Accuracy 90.52% and Validation Accuracy 82.03% are relatively close. The training loss and validation loss are also relatively close. This is a sign of good fit. The model is able to classify the images with 82% Validation Accuracy.

## Technologies Used
- Tensorflow- version 2.17.0
- Keras     - version 3.4.1
- Pandas    - version 2.1.4
- Augmentor - version 0.2.12
- Numpy     - version 1.26.4
- SNS		- version 0.13.1

## Acknowledgements
As part of UpGrad IITB Programme, a case study on "Melanoma Detection Assignment" was taken and applied the learnings from the Deep Learning CNN Module.

## Contact
Created by [@lattalavijaysekhar] - feel free to contact me!
