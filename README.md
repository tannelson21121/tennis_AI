
# Tennis Analysis

## Introduction
Centered on refining machine learning and computer vision abilities, this project delves into the analysis of tennis players in videos to quantify their speed, ball shot velocity, and shot count. We will leverage on YOLO (You Only Look Once) for players and tennis ball detection, and harnessing CNNs (Convolutional Neural Networks) for court keypoint extraction.

## Output Videos
Here is a screenshot from one of the output videos:

![Screenshot](output_videos/screenshot.jpeg)

## Models Used
* YOLO v8 for player detection
* Fine Tuned YOLO for tennis ball detection
* Court Key point extraction

## Training
* Tennis ball detector with YOLO: training/tennis_ball_detector_training.ipynb
* Tennis court keypoint with Pytorch: training/tennis_court_keypoints_training.ipynb

## Requirements
* python3.8
* ultralytics
* pytroch
* pandas
* numpy 
* opencv
