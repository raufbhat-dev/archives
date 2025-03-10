# raufbhat-dev Projects Repository

This repository contains the codebase for various projects undertaken by **raufbhat-dev**.

## Files

### 1. CatheterLocation.ipynb

This is the code for the Kaggle competition **Ranzcr CLIP - Catheter and Line Classification**.

#### About this Competition
In this competition, the goal is to detect the presence and position of catheters and lines on chest X-rays using machine learning. The dataset contains 40,000 images for training and testing the model, where the objective is to categorize a tube placement that is poorly placed.

#### What Files Are Needed?

- **train.csv**: Contains image IDs, binary labels, and patient IDs.
- **test**: Test images.
- **train**: Training images.
- **train_annotations.csv**: Contains segmentation annotations for training samples (some samples may not have annotations).
- **TFRecords**: Available for both train and test (and for the hidden test set).

The competition is a code-only competition, and there is a hidden test set (approximately 4x larger, with ~14k images).

#### Columns in train.csv

- **StudyInstanceUID**: Unique ID for each image.
- **ETT - Abnormal**: Endotracheal tube placement abnormal.
- **ETT - Borderline**: Endotracheal tube placement borderline abnormal.
- **ETT - Normal**: Endotracheal tube placement normal.
- **NGT - Abnormal**: Nasogastric tube placement abnormal.
- **NGT - Borderline**: Nasogastric tube placement borderline abnormal.

#### Link to Kaggle Competition

For more information, visit the [Kaggle competition page](https://www.kaggle.com/competitions/ranzcr-clip-catheter-line-classification).
