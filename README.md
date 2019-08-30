# Image Recognition Project
For this project we have decided to apply the knowledge of the BootCamp course on AI. We have mixed the Machine Learning models with computer vision. 
The main point is to find the most effective system to do personalized face recognition. Based on class understanding we have decided to compare four different systems.
  -CNN from scratch
  -Transfer Learning
  -OpenCV
  -YOLO
Our first impression is that YOLO probably is the one that is going to give us the best performance,due to the fact that is being used in many areas, even the fact that it is quite slow in the performance. In second place, or the one that probably also works really well is the Transfer Learning.

## Main Points of CNN and Transfer Learning:
### Pre-Processing
For this models we need to do a training with a large set of images but were able to recollect 34 so we should find a way to train more images, the best way to solve this was to do image aumentation, using three types of rotation, applying noise and mirror effect we were able to have 184 images.

![Normal](img_readme/normal.png)
![Edited](img_readme/edited.png)

### Model
#### The CNN model and layers that we used were:
![Edited](img_readme/cnn_model.png)
#### The transfer learning:
We choosed MobileNetV2

#### Conclusions
Once we did both programs and trained them we got an unexpected result, for us what gived us better accuracy and performance was the cnn from scratch that we were able to achieve an accuracy of 95%. Probably due to the images that we've used for training the model works really well with light but against the light isn't as good as we expected.
