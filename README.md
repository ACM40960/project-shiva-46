[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/foXtNvtG)


<p align="center"> AI IMAGE DETECTION - WEED DETECTION </p>
<p align="center"> DINESH ETUKURU 20200242 22201745 SHIVAAMRUTH UPPALA </p>

<br>

## Description:

In modern agriculture, optimizing crop yield is vital amidst weed-related challenges. We tackle this by innovatively employing CNNs and Darknet to distinguish crops from weeds. 

<br>



## Goal:

Develop and optimize a tailored object detection model by seamlessly integrating YOLO architecture into Darknet. Leveraging CNNs enhances accuracy and efficiency, enabling precise crop and weed differentiation in agricultural images. This project aims to establish a foundation for effective weed management and cultivation strategies.

<br>


## DataSet:

We have collected 2000 images containing a diverse representation of both weed and crop. This dataset includes prior information regarding bounding boxes and  class labels,  recorded within a dedicated text file. This text file provides essential information, including class labels, Normalized coordinates (X and Y), as well as dimensions (Width and Length).


<br>


## Setup:


  # How to use this repo?

  This Repository is diveded in two part:-

    1. Training 
    2. Performig detection using pre train model
        - Using openCV (skip installation using requirements.txt file)

<br>
 
## Training:-
 
 * For traning you have to clone repo and copy all files from `WeedDetectionSystem` folder and paste it in google drive.

 * Now from drive open main.ipynb file and you will get all documentation regarding it within the file.


<br>

### setting up environment:-

 * You need anaconda for this, if you don't have click below 

   [click here](https://www.anaconda.com/blog/anaconda-individual-edition-2021-11)

 * Inside the WeedDetectionSystem folder , you will find testing_and_detection folder. Download this folder and save it in your local system. 

 * Open Anaconda and upload the folder  testing_and_detection.
   Open Anaconda launcher : 

   Select the "file option" --> Open from path --> provide path --> Open. 

   path ex: C:\Users\SHIVAAMRUTH UPPALA\OneDrive\Desktop\WeedDetectionSystem\testing_and_detection.


## Performig detection using pre-trained model

  
  * For detection you need weights for network. And these weights files is present in the below link and must be placed in this path into -->WeedDetectionSystem-->testing_and_detection-->data-->weights. 

 [click here](https://drive.google.com/open?id=1-Aam2D-fqnwecbeHwa4rtzxtNjwcDkP6)

  * open [Weed_Image_Recognition.ipynb] under WeedDetection-->testing_and_detection-->detection and run each cell for results. 


