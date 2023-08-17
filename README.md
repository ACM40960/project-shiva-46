<h1 align="center">AI Image Recognition - Weed Detection</h1>
<h3 align="center">Dinesh Etukuru 20200242 || Shivaamruth Uppala 22201745</h3>

<p align="center">
  <img src="https://github.com/ACM40960/project-shiva-46/blob/main/images/weedimg.jpeg" alt="Weed Detection" width="500"/>
</p>

## Introduction

In the realm of modern agriculture, optimizing crop yield is a paramount challenge amidst the complexities posed by weeds. We embark on a pioneering journey, harnessing the power of Convolutional Neural Networks (CNNs) and Darknet to demarcate crops from weeds with unprecedented precision.

## Goal

Our endeavor is to architect and refine a bespoke object detection model. We ingeniously fuse the YOLO architecture into the Darknet framework. Amplified by the capabilities of CNNs, our approach elevates accuracy and efficiency, enabling the meticulous differentiation of crops and weeds within agricultural images. This undertaking forms the bedrock for effective weed management and cultivation strategies.

## Dataset

A curated collection of 2000 images offers a multifaceted representation of both weed and crop scenarios. This dataset is augmented with crucial bounding box and class label information, meticulously recorded within dedicated text files. These files encapsulate vital metadata, including class labels, normalized coordinates (X and Y), and dimensions (Width and Length).

## Setup

### Repository Structure

This repository is organized into two primary segments:

1. **Training**: Detailed instructions for training the model can be found in `WeedDetection/main.ipynb`.
2. **Performing Detection**: The `testing_and_detection` folder houses assets for running detection.

### Training

1. Clone this repository and upload the contents of the `WeedDetection` folder to your Google Drive.
2. Open `main.ipynb` in Google Drive for comprehensive training documentation.

### Performing Detection

1. Obtain the trained weights for CNN from the specified location and place them within `WeedDetection/testing_and_detection/data/weights`.
2. Access `WeedDetection/testing_and_detection/detection/Weed_Image_Recognition.ipynb` and execute each cell for insightful results.

### Weight File

For your convenience, we have already generated the weight file, accessible through this [Google Drive link](https://drive.google.com/file/d/1AOxCaQqy_AY33fjcJWxemu5iwIJ4jvC3/view?usp=sharing). This proactive measure significantly reduces the required training time, which would otherwise span 6-7 hours.

<div align="center">
  <p><strong>Let's embark on a journey of precision and innovation in agricultural image analysis.</strong></p>
</div>
