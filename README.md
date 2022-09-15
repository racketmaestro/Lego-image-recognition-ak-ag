# Lego motion detection and image classification

This repository contains two main folders of scripts. Firstly, the Computer_files folder contains scripts to create and train a lego technic image recognition CNN model using Tensorflow. Secondly, the RPI_files folder contains scripts and files needed for motion detection using picamera live feed, that when deployed together with the model, is able to classify lego pieces in realtime.

The database contains a small sample size of images. The models in the models folder were trained with 6000 images spanning across 7 possible categories of lego technic. It achieved 95% testing accuracy from an 80/20 split between training and testing data.

More images can be taken by editing the motion_detection_and_image_classification.py script.

The motion detection portion of the RaspberryPi script was adapted from pyimagesearch's project 'Building a Raspberry Pi security camera with OpenCV' and can be found at
https://pyimagesearch.com/2019/03/25/building-a-raspberry-pi-security-camera-with-opencv/


