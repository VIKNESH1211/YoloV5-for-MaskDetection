# YoloV5-for-MaskDetection
![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=Python) ![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git) 
---
# Data_set
The data set comprises of images of people wearing masks and not wearing a mask
and I have mannualy annotated the images using MakeSense AI and the annotations are
extracted in yolo format .i.e the label file for an image contains the class as well as
the coordinates for the bounding box , the first two numbers of the after the class represents
the centre point of the bounding box the next two point represents height and width.
# Training
The model was Trained using built in Train.py file from the Yolov5 frameWork 
the EPOCHS was taken as a hyperparameter and was set to 150 , BatchSize was set to 16
and model was trained successfully and weights were obtained
# Accuracy
A mAP score 0.995 was achieved 
Graphs was obtained using TensorBoard
![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)
