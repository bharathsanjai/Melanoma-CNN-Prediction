# Melanoma-CNN-Prediction

# Project Name
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Project pipeline

**Data Reading/Data Understanding** → Defining the path for train and test images 

**Dataset Creation** → Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.

**Dataset visualisation** → Create a code to visualize one instance of all the nine classes present in the dataset 

**Model Building & training :** 

Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser and loss function for model training
Train the model for ~20 epochs
Write your findings after the model fit. You must check if there is any evidence of model overfit or underfit.

**Chose an appropriate data augmentation strategy to resolve underfitting/overfitting**

**Model Building & training on the augmented data :**
Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser and loss function for model training
Train the model for ~20 epochs
Write your findings after the model fit, see if the earlier issue is resolved or not?

**Class distribution: Examine the current class distribution in the training dataset** 
- Which class has the least number of samples?
- Which classes dominate the data in terms of the proportionate number of samples?

**Handling class imbalances:** Rectify class imbalances present in the training dataset with Augmentor library.

**Model Building & training on the rectified class imbalance data :**
Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser and loss function for model training
Train the model for ~30 epochs
Write your findings after the model fit, see if the issues are resolved or not?

## Technologies Used
- Python version:  3.10.12
- TensorFlow version:  2.12.0
- GPU 


## References
- This project was inspired by [Images recognition](https://www.tensorflow.org/tutorials/images/classification)
- This project was based on [tf libraries](https://www.tensorflow.org/api_docs/python/tf/keras/utils/image_dataset_from_directory)


## Contact
Created by [@githubusername] - feel free to contact me!
