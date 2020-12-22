# Thermal-Image-segmentation
Neural Networks and Deep Learning Course Project

This project aims at achieving high accuracy segmentation on Infrared based Thermal images. As a first step, Single class segmentation is done for obstructions (pedestrians and cars classified into one class) identified on a dataset acquired by KAIST[1] with segmentation masks created by Ghose. Et al[2]. Using this a benchmark, another dataset acquired by the Northeastern University’s robotics department using the NUANCE autonomous driving car to collect dataset around the Boston area is used to test the accuracy of segmentation by the network and show the efficiency of segmentation masks created using different mathematical models. U-Net which is Convolutional Neural Network architecture developed by Olaf et al, for biomedical image segmentation is considered the framework to solve this problem which with further improvement proves to be a viable model. Upon testing different types of masks, to Zero binary threshold method was used to create masks segmenting the obstructions with a thermal reading. The predicted segmentation on the NUANCE validation dataset has a binary cross entropy loss of 0.118

[1]https://sites.google.com/site/pedestrianbenchmark/
[2]https://github.com/Information-Fusion-Lab-Umass/Salient-Pedestrian-Detection
