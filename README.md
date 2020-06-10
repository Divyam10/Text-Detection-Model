# Text-Detection-Model
Text Detection Model trained with Precision Score of 98% on Test Set of 200 images. 
===================

## Description
Text detection model build on fine tuning Faster Rcnn Inception coco V2 model  http://download.tensorflow.org/models/object_detection/faster_rcnn_inception_v2_coco_2018_01_28.tar.gz
Precision Score of 98%. 
It was trained on Coco Text Dataset V2 by just using one class of "machine printed- legible"



## Setup
1. Install Tensorflow Object Detection API from https://github.com/tensorflow/models.git
2. clone my repo in models/reseaarch/


- Run it from webcam
$ python Object_detection_webcam.py

- Run it on an image
$ python Object_detection_image.py

- Run it on a video
$ python Object_detectionvideo.py

## Samples 
### 5 iamges - 1 video file test - 1 webcam test
![alt text](https://github.com/Divyam10/Text-Detection-Model/blob/master/Container%20images/01.png)
![alt text](https://github.com/Divyam10/Text-Detection-Model/blob/master/Container%20images/02.png)
![alt text](https://github.com/Divyam10/Text-Detection-Model/blob/master/Container%20images/03.png)
![alt text](https://github.com/Divyam10/Text-Detection-Model/blob/master/Container%20images/04.png)
![alt text](https://github.com/Divyam10/Text-Detection-Model/blob/master/Container%20images/05.png)
[![Watch the video](https://i.imgur.com/vKb2F1B.png)](https://github.com/Divyam10/Text-Detection-Model/blob/master/Container%20images/7.mp4)
[![Watch the video](https://i.imgur.com/vKb2F1B.png)](https://github.com/Divyam10/Text-Detection-Model/blob/master/Container%20images/06.mp4)
## Scope
1. Recall can be increased by traninig it on illegible dataset from coco 
2. Handwritten text can also be detected if required.







