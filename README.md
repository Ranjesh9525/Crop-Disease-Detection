Here's how you can structure the content for your `README.md` file:

---

# Crop Disease Detection
### A Deep Learning Project

## Introduction
- Agricultural productivity is crucial for a nation's economic development.
- Early identification of plant diseases is vital for global health and well-being, making it essential to control diseased leaves during crop growth stages.
- Enhancing crop yields is particularly important in regions with food scarcity.
- Crop losses due to plant diseases result in reduced income for farmers, higher consumer prices, and significant economic impact.
- Limited access to disease-control methods leads to annual losses of 30-50% for major crops in various countries.
- Therefore, detecting crop diseases is vital for economic progress.

## Problem Motivation
- Agriculture plays a pivotal role in the Indian economy, contributing 20.2% to the GDP in 2020-21, up from 18.4% in 2019-20.
- Traditionally, human raters are employed for plant disease identification, a time-consuming, costly, and sometimes error-prone process.
- Continuous monitoring of large farms involves high costs and the repetitive involvement of a large group of experts.
- This motivated the automation of the process, employing deep learning classifiers to improve accuracy and efficiency.

## Problem Statement
- Develop a system to detect and differentiate between various crop diseases across multiple plant types.
- Implement object detection algorithms to identify diseased areas in crops based on features such as color, wilt, leaf spots, and unusual leaf size.
- Select appropriate neural networks for accurate classification.

## Objective
1. The primary objective is to classify images of specific crops as healthy or diseased, identifying the specific disease if present.
2. Utilize deep convolutional neural networks (D-CNN) and image processing techniques to accurately identify plant diseases based on features like color and leaf spots.
3. Develop a web-based application to enable widespread use, allowing a large number of users to easily determine crop diseases.

## Dataset Description

### Original Dataset
- The dataset includes 10 classes of diseases affecting tomato leaves:
  - Tomatomosaicvirus
  - Target Spot
  - Bacterial spot
  - Tomato Yellow Leaf Curl Virus
  - Late blight
  - Leaf Mold
  - Early blight
  - Spider mites (Two-spotted spider mite)
  - Tomato (healthy)
  - Septoria leaf spot
- The dataset contains:
  - 10,000 images for training
  - 1,000 images for validation
- Images were taken at different angles, backgrounds, and lighting conditions with a resolution of 255x255 pixels.

For more details about the dataset, refer to the [Original Dataset on Kaggle](https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf).

### Augmented Dataset
- The augmented dataset now includes:
  - 18,345 images for training
  - 4,585 images for testing
- Image size: 255x255 pixels
- Augmentation techniques applied: flipping, rotation, blur, relighting, random cropping, scaling, shearing, zooming, and horizontal flipping.

For more details about the augmented dataset, refer to the [Augmented Dataset on Kaggle](https://www.kaggle.com/datasets/noulam/tomato).

## Models Implemented
We have successfully implemented five models for detecting diseases in tomato plants:
1. CNN (with 3 different variants)
2. INCEPTION-v3
3. VGG-16
4. VGG-16 with Fine-Tuning
5. VGG-19

## Group Members
- Ranjesh Kumar ROY - 21cs3039
- Rajiv Yadav - 21cs3038
- Chaitanya Raj - 21cs3012

---
#   C r o p - D i s e a s e - D e t e c t i o n  
 #   C r o p - d i s e a s e - D e t e c t i o n  
 