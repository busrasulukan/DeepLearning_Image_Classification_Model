 
[![LinkedIn][linkedin-shield]][linkedin-url] 
# Introduction to Deep Learning: Version 1 
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
  </a>

  <h1 align="center">  A Basic Image Classification Model</h1> 

  

👨‍💻 In this repository, a simple implementation of an image classification machine learning model using theFastai library has been made.
## 1. Data Preparation:
📝 The code starts by listing files in the "data" directory, which contains subdirectories like "happy" and "sad" representing different classes of images.
## 2. Exploratory Data Analysis (EDA):
📝It displays the first image in the "happy" class to provide a visual understanding of the data.
📝Another part of the code prints information about the shape and color channels of the first image.
## 3. Model Building:
📝The code then proceeds to build a deep learning model using the fastai library. It uses a pre-trained ResNet34 architecture for transfer learning on the image classification task.
📝The model is trained on the provided dataset for five epochs with data augmentation techniques.
## 4. Model Evaluation:
📝After training, the code evaluates the model's performance using a confusion matrix, showing the accuracy and loss for each epoch.
📝It further explores the true positives, false positives, true negatives, and false negatives to understand the model's behavior on specific examples.
![image](https://github.com/busrasulukan/DeepLearning_Image_Classification_Model/assets/129671358/ddae2d7e-2f5b-4ba0-83c8-c05929534abd)

## 5. Interpretation and Visualization:
📝The code includes functions to visualize the top losses, true positives, false positives, true negatives, and false negatives.
📝The selected samples are plotted to provide insights into the model's predictions and misclassifications.
![image](https://github.com/busrasulukan/DeepLearning_Image_Classification_Model/assets/129671358/f7b2955f-79b7-42dc-9eb3-10eec2bce68e)


📖 In summary, the model aims to classify images into emotional categories and is designed to provide insights into its decision-making process through visualization and interpretation of results. The implementation combines fastai's simplicity with powerful deep learning capabilities for image classification tasks.



[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]:https://www.linkedin.com/in/b%C3%BC%C5%9Fra-sulukan-82299a177/
