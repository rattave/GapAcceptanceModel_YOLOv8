# GapAcceptanceModel_YOLOv8 (A Comparative Study on Gap Acceptance Behavior of Motorcycles Using Video Data at Intersections)

## Overview :
This project builds a Gap Acceptance Model based on the combination of straight or right-turn motorcycle behavior at T-shaped intersections and the presence of oncoming four cars.
Using this, we analyze and compare different vehicle combinations to improve safety and traffic flow at intersections.

## Main Features (Video Processing) 
- Object Detection : Based on Ultralytics YOLOv8
- Object Tracking : DeepSORT + mars feature extractor
- Speed Calculation : Frame-based displacement for distance and speed estimation
- Data Storage : Save CSV files containing unique IDs, vehicle direction, speed, time, gap and distance gap

## Execution Code
- 'Day&Nightv8_motorModel.ipynb' : Training process to improve object recognition accuracy for motorcycles by fine-tuning YOLOv8 models
- 'YOLO_Deepsort_v2_FINAL.ipynb' : Final code for object detection and tracking using trained models
- 'Description.ipynb' : Additional description and project notes

## HTML Results (html folder)
- 'Day+Nightv8_motorModel.html'
- 'YOLO_Deepsort_v2_FINAL.html'
- Description.html

## Demo GIF
- 'yolov8.mp4' : Video applying the trained model to sample video data captured at intersections

## More Detailes
https://www.notion.so/Gap-Acceptance-23879f19815e80b5a2e3ed65144cb766?source=copy_link

> This repository is intended for portfolio viewing purposes. The raw data is not disclosed due to size and licensing constraints.
> Instead of full reproducibility, code outputs (COLAB/HTML/MP4) are provided.
