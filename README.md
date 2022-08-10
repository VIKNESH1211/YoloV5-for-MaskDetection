# YoloV5-for-MaskDetection
![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=Python) ![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git) ![colab](https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-colab-small.png | width=100)
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
and model was trained successfully and weights were obtained.
# Accuracy
A mAP score 0.995 was achieved 
Graphs was obtained using TensorBoard
![TensorBoard graphs of the training](https://github.com/VIKNESH1211/YoloV5-for-MaskDetection/blob/main/Train/Tensor_board.pdf).
# Detection
The trained model gave satisfactory measure of confidence in the validation data , which confirms that the model is not going through overfitting.
