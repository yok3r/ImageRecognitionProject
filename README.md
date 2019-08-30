# Image Recognition Project
For this project we have decided to apply the knowledge of the BootCamp course on AI. We have mixed the Machine Learning models with computer vision. 
The main point is to find the most effective system to do personalized face recognition. Based on class understanding we have decided to compare four different systems.
  -CNN from scratch
  -Transfer Learning
  -OpenCV
  -YOLO
Our first impression is that YOLO probably is the one that is going to give us the best performance,due to the fact that is being used in many areas, even the fact that it is quite slow in the performance. In second place, or the one that probably also works really well is the Transfer Learning.
## Pre-processing
When we started to train the first two models we realised that we needed lot of images but we only were able to recollect 34 so we should find a way to train more images, the best way to solve this was to do image aumentation, using three types of rotation, applying noise and mirror effect we were able to have 184 images.
![Normal](img_readme/normal.png)
![Edited](img_readme/edited.png)
## CNN from scratch
For the model we used 147 images of each label to train and 37 to do the test. We have used keras ans the Sequential model.
![Edited](img_readme/cnn_model.png)
We have used four convulotional layers
## Transfer Learning using MobileNetV2
