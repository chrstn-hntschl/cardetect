# cardetect
A simple cardetector based on OpenCV

## Introduction
This repository contains source code for training and testing a simple car detector based on Robert Laganière's book *OpenCV Computer Vision Application Programming Cookbook* [link](https://www.packtpub.com/application-development/opencv-3-computer-vision-application-programming-cookbook).

### Running
In order to compile and run the detector, I prepared a small docker file that will:

1. Set up Ubuntu Linux 14.04 as base image
2. Install OpenCV from ubuntu repository
3. Pull the source code as well as all required resources from this guthub repository
4. Compile the source code
5. Train a car detector using data from [UIUC](http://cogcomp.cs.illinois.edu/Data/Car/)
6. Test the car detector on unseen data.

