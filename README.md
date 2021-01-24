# Object Detecting and Counting using Yolo V3 weights with OpenCV

This repo contains the implementation of object counting algorithm using yolo and OpenCV. 

# How to run?

Before you run, to obtain predictions using opencv dnn module, you will need to get yolo v3 weights. To get them you can directly run python or ipython notebook or you can use the following link:
```
!wget https://pjreddie.com/media/files/yolov3.weights
```
After you downloaded the weights, you should move them to the models folder.

All required libraries can be found in requirements.txt file. You can easly install required libraries and run python or ipython notebook and detect and count objects in the coco dataset.

Another way to run is using Google Colab link. You don't have to install anything since all the libraries are default installed in colab. You can just use new paths for your video or image files and thats it!

Link for the Google Colab link:

https://colab.research.google.com/drive/1pUzP60JgUc-Z6La1I7N7Li6X4UIj9BC2?usp=sharing

# Requirements

```
numpy==1.19.5
opencv-python==4.1.2
```
 
 The thing that I have done is all listed as follow: 

1.	Feeding an image to python script, it will show the image with bounding boxes.

2.	It will print object counts and names in the terminal.

3.	Orthomosaic maps are created with an open drone map.

4.	I add object names and count to the right corner of the frame

5.	I should be able to give a video and process it 

6.	I implement using colab to make it usable and reproducible

7.	Colab return outputs from the terminal and also returns a processed video file

8.	2 different functions for image (Orthomosaic map) and video (DJI Video)

9.	Video continuously prints the object names and counts for each frame and finally output the processed (bounding boxes for each object and at the right corner object counts will be shown) video.

10.	For the image the same processing will be applied and output image will have shown and saved to be downloaded. 

11.	Finally, all the code will be added to a github repo with explanations such as requirements and installation steps.

12.	Google colab link will be shared to produce results easly.

13.	Project will be able to count and detect objects in this dataset COCO Dataset which is providing the label version of the 80 dataset. https://github.com/pjreddie/darknet/blob/master/data/coco.names


