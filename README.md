# Melanoma Detection

> Melanoma detection using CNN Model.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

## General Information

- Objective is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- This project uses a dataset of about 2357 images of skin cancer types. The dataset contains 9 sub-directories in each train and test subdirectories. The 9 sub-directories contains the images of 9 skin cancer types respectively.

## Conclusions

- 3 CNN models were built
- Base model with few layers without any special data treatment - proved to be overfitting
- Model 2 with Augumentation layer and few dropout layers - fixed overfitting issue, but didn't perform well (underfit)
- Model 3 with class imbalance fixed works well and is not overfitting or underfitting.

## Technologies Used

- Keras library, tensorflow is used to build CNN model.

## Contact

Created by [@VJ-Jain] - feel free to contact me!
