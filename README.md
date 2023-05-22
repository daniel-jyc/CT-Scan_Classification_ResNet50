# CT-Scan_Classification_ResNet50


Dataset Source: https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images

## Introduction
This project aims to create a deep learning solution to accurately detect and classify abnormal patterns in chest CT-Scans into three common chest cancer types, including Adenocarcinoma, Large cell carcinoma, and Squamous cell carcinoma. 

The Association of American Medical Colleges has pointed out a shortage of radiologists. While the interpretation of medical images requires extensive training and expertise, deep learning models that are properly developed and fine-tuned can assist in automating analysis and classification of CT-Scans, which benefits early detection.

The solution could reduce workload of radiologists and improve the efficiency of the diagnostic process.

## Base Model Used
ResNet50

## Model Structure
![model](https://github.com/daniel-jyc/CT-Scan_Classification_ResNet50/assets/124631103/d7990272-3d24-4c99-80d2-bfb80fe2892e)

## Training Result
![epoch_accuracy (1)](https://github.com/daniel-jyc/CT-Scan_Classification_ResNet50/assets/124631103/38574b3b-180a-4a25-92f7-6d2c10ca3566)
Epoch vs Accuracy (Orange: train, Blue: validation)
![epoch_loss-_1_ (1)](https://github.com/daniel-jyc/CT-Scan_Classification_ResNet50/assets/124631103/96bbad91-aade-42a2-aee1-4960836934ba)
Epoch vs Loss (Orange: train, Blue: validation)

The validation accuracy is similar to the train accuracy. The validation loss is slightly higher than the train loss. We could conclude that our model is experiencing slightly overfitting with 39 epochs of training.

