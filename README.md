# Breast-cancer-detection-with-CNN-and-GradCAM
Detection of breast cancer using CNN and enhanced visualisation using GradCAM
## Overview
Our project aims to employ Convolutional Neural Networks (CNN) for accurate breast cancer detection by classifying it as benign or malignant through medical imaging. The integration of GradCAM (Gradient-weighted Class Activation Mapping) enhances the interpretability of the CNN's predictions by generating heatmaps that highlight critical regions in mammogram images. This approach not only improves diagnostic accuracy but also provides valuable insights for clinicians to understand and trust the model's decisions. The project emphasizes the synergy between advanced CNN techniques and GradCAM for a more effective and transparent breast cancer detection methodology.

## Features
CNN Architecture: Utilizes a sophisticated CNN architecture tailored for medical image analysis to effectively capture intricate patterns indicative of breast cancer.

GradCAM Visualization: Implements GradCAM to enhance the interpretability of the model's predictions by generating heatmaps that highlight the regions in mammogram images contributing most to the decision.

## Data Description:
The project utilizes mammography images from the INbreast database, collected between 2008 and 2010, containing 410 images across various breast diseases. Focusing on 106 breast mass images, data augmentation techniques increase the dataset to 7632 images. Preprocessing involves contrast enhancement using CLAHE. The preprocessed and augmented dataset, crucial for the project's implementation, is available on GitHub. The dataset, containing 7632 mammography images with enhanced diversity and features, contributes to the robustness and effectiveness of the breast cancer classification model.
Link to dataset: https://github.com/LearnToCode180/Breast-Cancer-Classification/blob/master/DataSet.zip
