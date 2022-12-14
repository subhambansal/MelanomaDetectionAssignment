# Multiclass classification model using a custom convolutional neural network in TensorFlow. 
> Problem statement: 

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion
 
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
> Solution Stratgy: 
Divided analysis in below mentioned border catogry
### Pipeline

- Data Reading/Data Understanding
 Dataset Creation
- Dataset visualisation
- Model Building & training
- Chose an appropriate data augmentation strategy to resolve underfitting/overfitting
- Model Building & training on the augmented data
- Class distribution
- Handling class imbalances
- Model Building & training on the rectified class imbalance data


## Conclusions
- It has been Observed when we ran the first model with Raw data provided with Rescaling. Though model Train accuracy was good but it realuts in loss with Validation data Which Results in Overfitting and overall Accuracy of 50%
- Data Augmentation technique applied and Resolving the calss imbalce result in good imporvement where no big loss with valdation found.Overall accuracy reached to 77%

## Technologies Used
-  Google Colab with Python using GPU for CNN.
-  library - Matplotlib,plotly,Tanserflow and Keras

## Acknowledgements
Credit
- This project is a part of Study by Upgard Learning

## Contact
contributors 
Subham Bansal [@subhambansal] - contact er.subhambansal@gmail.com

## License
This project is open source available for study