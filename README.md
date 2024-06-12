# Project Name
Melanoma Detection Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Result](#Result)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#Contact)

## General Information
We aim to develop a Convolutional Neural Network (CNN) model capable of accurately detecting melanoma, a potentially deadly form of skin cancer. Early detection is critical, as melanoma accounts for a significant portion of skin cancer-related deaths. Our solution involves evaluating skin images and alerting dermatologists about potential melanoma cases. By automating this process, we can significantly reduce the manual effort required for diagnosis.

The dataset, sourced from the International Skin Imaging Collaboration (ISIC), comprises 2357 images representing various oncological diseases—both malignant and benign. These images have been meticulously categorized based on ISIC’s classification. Notably, the dataset includes melanomas and moles, which are slightly more prevalent. The specific diseases covered include:

* Actinic keratosis
* Basal cell carcinoma
* Dermatofibroma
* Melanoma
* Nevus
* Pigmented benign keratosis
* Seborrheic keratosis
* Squamous cell carcinoma
* Vascular lesion

Our goal is to leverage this diverse dataset to build an accurate and reliable model for melanoma detection.

## Technologies Used
- Python
- TensorFlow
- Keras
- Augmentor
- NumPy
- Matplotlib
- OpenCV
- PIL

## Result
After training the model for around 50 epochs, the following results were achieved:

- Training Accuracy: 79%
- Validation Accuracy: 78%
- Training Loss: 0.5
- Validation Loss: 0.7

The model showed significant improvement in accuracy and reduced overfitting compared to earlier versions. Class rebalancing using data augmentation played a crucial role in achieving these results.

## Conclusions
The CNN model we’ve developed demonstrates encouraging outcomes in accurately detecting various skin cancer types. By harnessing deep learning methods and data augmentation, the model becomes a valuable tool for dermatologists in melanoma diagnosis and beyond. To enhance its performance further, consider gathering more diverse and balanced datasets and fine-tuning the model architecture.

## Acknowledgements
- This project was inspired by live session of upGrad on Convolutional Neural Networks.
- UpGrad tutorials on Neural Networks on the learning platform


## Contact
Created by [@samik0701]
