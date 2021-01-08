# Deep_Learning_Project_of_Waste_Management
<img src="https://github.com/cpuikin/Deep_Learning_Project_of_Waste_Management/blob/main/image/waste-classify-logo.png" width="1000" height="300" />

This project is train a model to classify the waste like human with Deep Learning.

# Aim
  - Train a model to see the way as human with Deep Learning.
  - Combining the use of robotic arms to classify waste effectively without days off.
  - Recycle the waste as much as possible to give a better environment.

# Data Set
  - https://www.kaggle.com/asdasdasasdas/garbage-classification (2500 images)
  - Images download from google (3500 images)

# Data Clean
  - All images are then converted into JPG files 
  - Delete the crashed image files
  - Dataset is divided into classes as cardboard, glass, metal, paper, plastic and trash 

# Model Creation
  - InceptionV3
  - InceptionResNetV2
  - VGG19
  
# Evaluation And Prediction
Overall trend: increase
Training accuracy for models are around 80% 
Splitting point from training and validation accuracy for:    V2 & V3:  at 0.63; VGG19: at 0.57 
Distance between training and validation: VGG19: 0.15; V3:0.1; V2: 0.05 (shortest distance)
However, accuracy of VGG19 is the highest

Most of them are correct except the cocacola can. It is incorrectly predicted as trash but it should be identified as metal.
Reason: Maybe color and logo of the can and glare of the can
As from our training data, most of  them are in silver color and most of them have the light reflection on the can. However, this cocacola can is in red and lack of glare.

CONCLUSIONS:
High Accuracy - InceptionV3 model can recognize the images with accuracy as high as 71.9%.
High Efficiency - 96 images can be processed in a minute. 
High Recyclability - model can properly identify the most toxic material “Plastic” to recycle.
Better Environment - more waste can be recycled and reused, a more  sustainable environment to live on. 
