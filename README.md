# Skin-Cancer-Detection

## Title: Skin Cancer Diagnosis with Pre-trained Models: A Comparative Study Using HAM10K


## Abstract
Skin cancer is a global health concern with increasing incidence rates. Early detection and intervention are critical for improving patient outcomes. This study hypothesizes that transfer learning applied to pre-trained deep convolutional neural networks can effectively classify skin lesions from dermoscopic images. Our primary objective is to determine if transfer learning can be effectively applied to the HAM10K dataset while maintaining high levels of explainability and accuracy. To achieve this, we employed a transfer learning approach on pre-trained deep learning architectures: ResNet50, InceptionV3, MobileNetV3, VGG-16-BN. A balanced HAM10K dataset was used for fine-tuning these models. To ensure data consistency, we performed separate up- and downsampling for the training and testing splits. Our standard workflow involved training the final layer of the models initially, followed by fine-tuning the entire model at a reduced learning rate. Model performance was evaluated using accuracy and F1-score metrics. Additionally, we generated explainability heatmaps using Score-CAM to compare the predictions of different models. Results indicate a promising performance. This study’s findings suggest that transfer learning is a promising approach for skin cancer classification. However, the models' generalization ability is limited due to the heavily imbalanced dataset, with a small number of images representing malignant lesions. Further research and development are necessary to improve model performance and generalization capabilities.

## Results
![image](https://github.com/user-attachments/assets/062aa15e-68ff-4091-b877-40c6153ee938)

## Heatmaps:

![image](https://github.com/user-attachments/assets/ce55a757-0d7b-403a-b2db-aed49ba47b40)

![image](https://github.com/user-attachments/assets/adf33516-4bed-4dc0-bfa9-563295a09085)

## Presentation:

[Transfer Learning for Skin Lesions Classification.pdf](https://github.com/user-attachments/files/16470122/Transfer.Learning.for.Skin.Lesions.Classification.pdf)


## Team Members:
* MohammadReza Toghyani
* Mohammad Sadegh Fallahi
* Zhanna Osipova
* Francisco Javier Ordoñez Araujo
* Karan Khandekar




