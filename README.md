# Rolling to Global shutter transformer 

The repository contains the code implementation of the final project of the Skoltech Deep Learning 2023 course. 

## Using stacking to improve neural optimal transport based style transfer models.

### Problem statement 
When shooting fast-moving objects on a camera with a rolling shutter, defects appear in the image that distort the true position of objects.

### Abstract
The idea of our project to transform images captured by rolling shutter cameras to global shutter images . Rolling shutter cameras capture images by scanning a scene over a period of time, resulting in distorted images with motion artifacts. To address this issue, global shutter cameras capture images instantaneously. The goal of the project is to evaluate the appearance of distorted objects and generate an image, as if obtained from a global shutter camera.  
As part of the project, we propose to first generate synthetic data, and as the project is further developed, proceed to training on experimental data obtained by recording from two types of cameras. As a possible solution, we consider end2end neural networks and ways to evaluate the convolution kernel. Additionally, a range of metrics such as MSE, PSNR, and SSIM will be used to evaluate the quality of the transformed images.
This approach is expected to improve the image quality and reduce the motion artifacts, making it applicable in various fields, including robotics, self driving, and computer vision.

### Datasets and Preprocessing

Dataset description 

### Example of results

Examples

## Repository structure and code usage instructions
### Structure

Structure 

### Instructions
###### Python Scripts for Local Machines
How to run experiment and train model

###### Notebooks for Collab
The self-explanatory notebook can be found at ```notebooks/notebook.ipynb``.

## Requirements


## Credits
- [Skoltech DL course](https://github.com/oseledets/dl2023) for the great DL course;
- [Weights & Biases](https://wandb.ai) for machine learning developer tools;
