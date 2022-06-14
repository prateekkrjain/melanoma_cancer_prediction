# Melanoma Cancer Prediction Case Study
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Dataset Details](#dataset-details)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contact](#contact)
* [License](#license)

## General Information
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Dataset Details

> Train and Validation datasets have been provided
+ Train dataset contains 2,239 samples from 9 distinct classes
+ Test dataset contains 118 samples from 9 distinct classes

## Conclusions
> Model fitness related
+ Augmentation definitely helped with the solving for both underfitting and overfitting
+ The final Train accuracy is 92% while the Validation accuracy is 81%
+ So, the model is still overfitting, but compared to before augmentataion it is much better
+ Also, we observe that the Validation accuracy curve is not smooth. For some epochs accuracy is very poor while for some it is very good. This is likely to be due to the constant/fixed learning rate, if we decline the learning rate with the increase in epochs, we might be able to get smoother validation curve.

> Class wise accuracy results
+ All the classes have F1 score greater than 80%, except for class - "actinic keratosis", which has 71% F1 score
+ Class - "melanoma" has F1 score of 89%
    + With 99% Precision - indicating that model is correct 99% of the times when it predicts Melanoma cancer 
    + Also, Recall of 81% - indicating that the model is able to capture/predict 81% of all the actual Melanoma cancer cases

## Technologies Used
- Python - version 3.7.13
- Numpy - version 1.21.6
- Pandas - version 1.3.5
- Matplotlib - version 3.2.2
- Tensorflow - version 2.8.2
- Google Colab

## Contact
Created by [@prateekkrjain](http://prateekkrjain.com) - feel free to contact me!)
