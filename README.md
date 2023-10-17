# Melanoma Detection
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- The data set contains the following diseases:
  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion
- In this assignment, we have build a multiclass classification model using a custom convolutional neural network in TensorFlow. To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- Dataset provided by Upgrad is being used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Initially, when we began with a basic CNN model, we noticed a case of overfitting. The training accuracy was considerably high, whereas the validation accuracy remained notably low.
- To address the overfitting problem, we introduced augmentation techniques into the CNN model. This allowed us to better grasp the subtle differences and commonalities between images, ultimately mitigating the overfitting.
- In addition to augmentation, we applied Batch Normalization and Dropout in tandem, leading to a more suitable model fit.
- The dataset exhibited class imbalance, prompting the utilization of an Augmentor pipeline to balance each class with 500 instances. This adjustment effectively resolved the overfitting issue.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python
- Numpy
- Matplotlib
- tensorflow
- pandas
- pathlib
- Augmentor
- GoogleColab

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by Upgrad Melanoma Detection Assignment.
- Wikipedia
- Medium
- StackOverflow


## Contact
Created by - [@sumanthan01]


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->