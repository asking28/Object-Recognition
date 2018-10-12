# Object-Recognition
I have applied Deep Learning algorithms **YOLOv2** and **YOLOv3** for the object detection task and then applied Non-max suppression which uses
Intersection Over Union (IOU) of two overlapping boxes to further reduce the number of bounding boxes. <br/>
I created my own custom dataset of my own image using Image labelling software and augmented data since number of images were far too less to train so large network. I used tensorflow to crop, flip and zoom the images and create bigger dataset for training. I found that the bigger datasets gave better results in recognizing and drawing bounding boxes of my face. <br/>
Training YOLOv3 to detect my face as an object gave an accuracy with recall of 69% with dataset algorithm never saw earlier.
