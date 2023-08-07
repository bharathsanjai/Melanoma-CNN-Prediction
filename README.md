# Melanoma-CNN-Prediction

## Table of Contents
* [Project Name](#project-name)
* [Dataset](#dataset)
* [Technologies Used](#technologies-used)
* [References](#references)

## Project Name
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Dataset

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

* Actinic keratosis
* Basal cell carcinoma
* Dermatofibroma
* Melanoma
* Nevus
* Pigmented benign keratosis
* Seborrheic keratosis
* Squamous cell carcinoma
* Vascular lesion

## Project pipeline

1. Data Reading/Data Understanding
2. Dataset Creation
3. Dataset visualization
4. Model Building & training
5. Choose an appropriate data augmentation strategy to resolve underfitting/overfitting
6. Model Building & training on the augmented data
7. Class distribution: Examine the current class distribution in the training dataset
8. Handling class imbalances
9. Model Building & training on the rectified class imbalance data


## Technologies Used
- Python version:  3.10.12
- TensorFlow version:  2.12.0
- GPU 


## References
- This project was inspired by [Images recognition](https://www.tensorflow.org/tutorials/images/classification)
- This project was based on [tf libraries](https://www.tensorflow.org/api_docs/python/tf/keras/utils/image_dataset_from_directory)


## Contact
Created by @bharathsanjai - feel free to contact me!
