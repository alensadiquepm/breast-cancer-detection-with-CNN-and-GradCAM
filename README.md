# breast-cancer-detection-with-CNN-and-GradCAM
Detection of breast cancer using CNN and enhanced visualisation using GradCAM
## Overview
This repository contains an implementation of a breast cancer detection model using Convolutional Neural Networks (CNN) with enhanced visualization through Gradient-weighted Class Activation Mapping (GradCAM). The model is designed to analyze mammogram images and provide accurate predictions regarding the presence of breast cancer.

## Features
CNN Architecture: Utilizes a sophisticated CNN architecture tailored for medical image analysis to effectively capture intricate patterns indicative of breast cancer.

GradCAM Visualization: Implements GradCAM to enhance the interpretability of the model's predictions by generating heatmaps that highlight the regions in mammogram images contributing most to the decision.

## Data Description:
The project utilizes mammography images from the INbreast database, collected between 2008 and 2010, containing 410 images across various breast diseases. Focusing on 106 breast mass images, data augmentation techniques increase the dataset to 7632 images. Preprocessing involves contrast enhancement using CLAHE. The preprocessed and augmented dataset, crucial for the project's implementation, is available on GitHub. The dataset, containing 7632 mammography images with enhanced diversity and features, contributes to the robustness and effectiveness of the breast cancer classification model.
Link to dataset: https://github.com/LearnToCode180/Breast-Cancer-Classification/blob/master/DataSet.zip
