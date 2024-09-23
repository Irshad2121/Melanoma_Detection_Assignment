# Project Name
> Melanoma Detection Using CNN


## Table of Contents
* CNN model used for melanoma detection
* L2 Regularization applied for better generalization
* Dropout layers used to address overfitting
* Data Augmentation to increase dataset variety
* Training and validation results visualized



<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Business Problem: Doctors, especially dermatologists, spend a lot of time looking at images to detect melanoma. If we can train a model to do this automatically, it can help doctors save time and focus on actual treatment.
- Dataset: We are using a dataset of about 2357 images. The images are divided into 9 types of skin cancer. Each type is in a separate folder under both the train and test datasets.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The CNN model performed better after adding L2 regularization and Dropout layers, which helped prevent overfitting.
- Data Augmentation was used (including rotations, flips, zooms, etc.) to artificially increase the variety of the training data, which helped the model generalize better to new images.
- Overfitting was reduced thanks to the added regularization and data augmentation, leading to a more balanced performance between the training and validation datasets.
- Further testing is still needed on larger and more diverse datasets to confirm how well this model generalizes in the real world.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- TensorFlow Version: 2.17.0
- Keras Version (via TensorFlow): 3.5.0
- Pandas Version: 2.2.2
- Augmentor Version: 0.2.12



## Contact
- Irshad Shaikh  https://github.com/Irshad2121/
