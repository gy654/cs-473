# Spacial Coordinate Prediction of a 4-fingered Robot Hand

This is the personal capstone project for the course CS-473 Intro to machine learning at NYU (Fall 2022). Many thanks to the instructor Lerrel Pinto [webpage](The baseline CNN model)for inspiration.

## Problem Statement
In this project, I work on state prediction of a 4-fingered robot hand given RGBD (RGB + Depth) images. I implement a simple supervised learning algorithm where you input RGBD images of the robotic hand from a top view, and output the positions (in meters) of the tip of each finger.  The evaluation metric is the root mean squared error (RMSE) loss.

## Repository structure
`baseline_model.ipynb` : contains the code for the baseline CNN model. The architecture of the model is inspired by vgg.
`restnet_model.ipynb`: contains the code for the model finetuned on resnet50. 
`capstone_report`: summary of experiment results



