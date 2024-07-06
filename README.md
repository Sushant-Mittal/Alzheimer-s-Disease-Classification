# Alzheimer's Disease Classification
## Aim :
The aim of this notebook is to get the best results from GhostNet_1x model to predict whether the provided MRI Brain scan has signs of Alzheimer's disease or not. It is a 4 class problem.

## Dataset Used :
We took the dataset from Kaggle, it has about 34k images of several patients MRI Brain scans. The link to the dataset is https://www.kaggle.com/datasets/uraninjo/augmented-alzheimer-mri-dataset.

## Model Used :
We used a customized version of Ghostnet_1x model, with added layers at the end. We used batch-normalization and an upgraded version of Softmax classifier i.e LogSoftmax. 

## Results:
We achieved very good results when the model was tested on test dataset. We got a accuracy of 99.06% on test dataset.

# Confusion Matrix
![Screenshot 2024-07-05 141940](https://github.com/Ayu0330/Alzheimer-s-Disease-Classification/assets/97387892/2c9da45e-67bf-47c8-b914-f749cc35d010)

# Classification Report
![Screenshot 2024-07-05 142000](https://github.com/Ayu0330/Alzheimer-s-Disease-Classification/assets/97387892/ae3ff808-ee7c-423d-ab84-df11d21b21a0)

# Class-wise Classification Report
![Screenshot 2024-07-05 143307](https://github.com/Ayu0330/Alzheimer-s-Disease-Classification/assets/97387892/00676f21-c93f-40fe-9b5c-20049f3edd9d)
