**Background:** For the final project, we are asked to identify a Deep Learning problem to perform Exploratory Data Analysis (EDA), as well as model analysis.  This project focuses on the Multi-Class Classification of images.  There is a movie called, "Planes, Trains and Automobiles" and this project is loosely based on the idea of comparing these vehicles -- except, instead of Automobiles, we utilize Trucks which are larger and may be more difficult to distinguish.  Since Convolutional Neural Networks (CNN) perform well on image classification tasks, CNN models were utilized and the results were compared to a pre-trained ResNet model, as well as Support Vector Classification.  

In a CNN, the Convolution layer slides a filter across the image to detect features, with subsequent Convolution layers building on the previous layers' representation.  Often, the Convolution layer is followed by Pooling and Dense layers. This structure is utilized below for our multi-class classification problem.  Given their structure, CNNs have excelled at other imaging, speech or video tasks.  People experience the impact of these models in their everyday lives -- whether it is tagging images in social media, online image search recommendations or reading medical images.

**Description:**  The dataset contains 2772 color (RGB) images which are 256 by 256 pixels of Airplanes, Locomotives (or steam locomotives to be specific) and Trucks.  The images were segmented in their respective classes on the images.cv website.  This Airplane-Locomotive-Truck dataset is a new dataset created by merging separate vehicle categories of Airplane, Locomotive and Truck images. Each set of images is segmented into folders for training, validation and testing.

**Table 1**

_Explanation of Data Fields with Description_

|Variable |	Description|  Data Type |   Image Size | Image Type | File Format|            
|:---------|:------------------|:-------------|:-------------|:-------------|:-------------|
|**File Name**	|Identification number of image| Alphanumeric | 256 x 256 | RGB | JPEG|


**Image Count:** 

* **Airplane:** 767 images
  
* **Locomotive:** 1300 images
 
* **Truck:** 705 images
  
* **Total Image Count: 2772 instances**

**Date:** February 2025

**Link:** https://images.cv
