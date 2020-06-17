# Indian-License-plate-detection-with-YOLOv3-using-Transfer-Learning
This repo helps in Image Segmentation of Indian License Plates using state-of-the-art YOLOv3 computer vision algorithm.

# Pipeline Overview

1. Getting started: Upload the vott-csv-export data folder in your Google Drive. Clone the https://github.com/AntonMu/TrainYourOwnYOLO in your Google Drive using Colab. This repo let's you train a custom image detector. 

2. Image Annotation

3. Training: Download pre-trained weights and tweaking the model according to our needs.

4. Inference: Detection of the license plate in the Testing Images. To carry out the testing make sure you've added the testing images in your Google Drive @ ILPR/TrainYourOwnYOLO/Data/Source_Images/Test_Images/

# Quick start

To train your own ILPR using YOLO object detector please run these files in order on Collab:

* [ILPR_0_GettingStarted](ILPR_0_GettingStarted.ipynb)
* [ILPR_1_ImageAnnotation](ILPR_1_ImageAnnotation.ipynb)
* [ILPR_2_Training](ILPR_2_Training.ipynb)
* [ILPR_3_Inference](ILPR_3_Inference.ipynb)

To make sure than everything run smoothly, it is recommended to keep the original folder structure of this repo!

# Results

<img src="Demo Testing/Testing Images/Capture1.jpg" alt="1" width="350"/> &emsp; &emsp; &emsp; <img src="Demo Testing/Detected Images/Capture1_licensePlate.jpg" alt="1" width="350"/>

<img src="Demo Testing/Testing Images/Capture.jpg" alt="2" width="350"/> &emsp; &emsp; &emsp; <img src="Demo Testing/Detected Images/Capture_licensePlate.jpg" alt="2" width="350"/>

# Acknowledgements
Huge thanks to [Anton Muehlemann](https://github.com/AntonMu) for his repository to train YOLO from scratch. This repo makes use of https://github.com/AntonMu/TrainYourOwnYOLO
