<p align="center"> AI IMAGE RECOGNITION - WEED DETECTION </p>
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


  # This Repository is diveded in two part:
  
    1. Training 
    2. Performig detection using pre train model
        - Using jupyter and openCV 

<br>
 
## Training:-
 
 * First, git clone the repository and copy all the files from `WeedDetectionSystem` folder and upload it in google drive.

 * Now, in the drive open the main.ipynb file, where you will find all documentation regarding training the model.

<br>

### Setting up environment:
 * First of all you need anaconda, if you don't have click below for the installation.
   
 [Anaconda here](https://www.anaconda.com/blog/anaconda-individual-edition-2021-11)

 * Next download and save the testing_and_detection folder to your local system from google drive. testing_and_detection folder is present inside the WeedDetectionSystem folder.
   
 * Open Anaconda launcher and upload the folder "testing_and_detection" here.
   # How?
   Select the "file option" --> Open from path --> provide path --> Open.
   path ex: C:\Users\SHIVAAMRUTH UPPALA\OneDrive\Desktop\WeedDetectionSystem\testing_and_detection.


## Performig detection using pre-trained model

  
  * For detection you need weights for network. And these weights files is present in the below link and must be placed in this path into -->WeedDetectionSystem-->testing_and_detection-->data-->weights. 

 [weights here](https://drive.google.com/open?id=1-Aam2D-fqnwecbeHwa4rtzxtNjwcDkP6)

  * open [Weed_Image_Recognition.ipynb] under WeedDetection-->testing_and_detection-->detection and run each cell for results. 



















