# Blood Cell Image Classification using CNNs
### Project Overview
This project is the first homework assignment for the "Artificial Neural Networks and Deep Learning" course (A.Y. 2024-2025). The objective is to develop a high-performing Convolutional Neural Network (CNN) to classify 96x96 RGB images of blood cells into eight distinct classes.

<img width="1024" height="546" alt="Image" src="https://github.com/user-attachments/assets/a080eb74-614d-4bdc-a5d0-df93113efb67" />

Our approach involves a thorough analysis of the dataset, extensive data preprocessing and augmentation, and the implementation of transfer learning techniques. We explored several pre-trained models, including ResNet50 and MobileNetV3Small, to serve as the feature extraction backbone for our classifier.

### Dataset Description
The dataset consists of 96x96 pixel RGB images of blood cells, categorized into eight different classes.

### Key Challenges & Characteristics
A preliminary analysis revealed several key challenges that informed our preprocessing and modeling strategies:

Class Imbalance: The dataset is significantly unbalanced, with some classes having a much larger number of images than others.
Data Quality: We identified 1806 duplicated images, many of which were identical illegitimate images.
Outliers: A subset of 321 images was found to have a strong blue color cast, which we treated as outliers.

The primary challenge was to build a model that generalizes well despite these data quality and distribution issues.
