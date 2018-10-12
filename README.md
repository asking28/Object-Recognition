# Object-Recognition
I have applied Deep Learning algorithms **YOLOv2** and **YOLOv3** for the object detection task and then applied Non-max suppression which uses
Intersection Over Union (IOU) of two overlapping boxes to further reduce the number of bounding boxes. <br/>
I created my own custom dataset of my own image using Image labelling software and augmented data since number of images were far too less to train so large network. I used tensorflow to crop, flip and zoom the images and create bigger dataset for training. I found that the bigger datasets gave better results in recognizing and drawing bounding boxes of my face. <br/>
Training YOLOv3 to detect my face as an object gave an accuracy with recall of 69% with dataset algorithm never saw earlier.<br/>
## Files Description
- my_5000.weights- This file contains weights of YOLOv3 tiny architecture trained for 5000 iterations on NVIDIA Tesla GPU which took aroung 8-10 hours. 
- my-big_1500.weights- This file contains weights of YOLOv3 architectue trained for 1500 architecture. It perrforms far better than 5000 iterations of Tiny architectue of YOLOv3.
- Test Data- It contains images and bounding boxes of the images that were used for testing .
- Imgs- This folder contains images that were predicted using these trained weights with bounding boxes and labels in it.
- bbox_txt- This folder contains Bounding boxes of teting images in the format (class centre_x centre_y width height) of the bounding boxes.
