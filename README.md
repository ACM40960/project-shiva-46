<p align="center"> AI IMAGE RECOGNITION - WEED DETECTION </p>
<p align="center"> DINESH ETUKURU 20200242 || SHIVAAMRUTH UPPALA 22201745 </p>

<br>

## Introduction:

In modern agriculture, optimizing crop yield is vital amidst weed-related challenges. We tackle this by innovatively employing CNNs and Darknet to distinguish crops from weeds. 

<br>

![](https://github.com/ACM40960/project-shiva-46/blob/main/images/weedimg.jpeg)

<br>

## Goal:

Develop and optimize a tailored object detection model by seamlessly integrating YOLO architecture into Darknet. Leveraging CNNs enhances accuracy and efficiency, enabling precise crop and weed differentiation in agricultural images. This project aims to establish a foundation for effective weed management and cultivation strategies.

<br>


## Dataset:

We have collected 2000 images containing a diverse representation of both weed and crop. This dataset includes prior information regarding bounding boxes and  class labels,  recorded within a dedicated text file. This text file provides essential information, including class labels, Normalized coordinates (X and Y), as well as dimensions (Width and Length).


<br>


# Setup :


  ## This Repository is divided into two parts:
  
    1. Training 
    2. Performig detection 
        - Using jupyter and openCV 

<br>
 
## Training:-
 
 * First, git clone the repository and copy all the files from `WeedDetection` folder and upload it in google drive.

 * Now, in the drive open the main.ipynb file, where you will find all documentation regarding training the model.

<br>

### Setting up environment:

 * First of all you need anaconda, if you don't have click below for the installation.
   
 [Anaconda here](https://www.anaconda.com/download)

 * Next download and save the `testing_and_detection` folder to your local system from google drive present under `WeedDetection` folder. 
   
 * Open Anaconda launcher and upload the folder `testing_and_detection` here.
   # How?
   * Select the "file option" --> Open from path --> provide path --> Open.
   * path example: C:\Users\SHIVAAMRUTH UPPALA\OneDrive\Desktop\WeedDetectionSystem\testing_and_detection.

## Performig detection:
  
  * For detection you need weights for CNN.
  * These weights file must be placed in the below mentioned path in your local system once the model is trained:
  *  -->WeedDetection-->testing_and_detection-->data-->weights.
  ###  Note:
   **Important**: We have already generated the weight file and placed it in the designated [Google Drive link](https://drive.google.com/file/d/1AOxCaQqy_AY33fjcJWxemu5iwIJ4jvC3/view?usp=sharing). This step was taken to minimize the training time required. If you decide not to conduct the training, you can utilize this file. Please be aware that training this model typically takes 6-7 hours.
  * Now, open `Weed_Image_Recognition.ipynb` under WeedDetection-->testing_and_detection-->detection and run each cell for results. 



















