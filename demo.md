### Training Semantic Segmentation Datasets for Autonomous Driving
## Objective:
 The main objective of Training semantic segmentation datasets for self-driving cars is to improve accuracy by taking appropriate measures.
## Description:
The main consideration is about Object detection and the task of recognizing and localizing multiple objects in a scene. Objects are usually recognized by estimating a classification probability and localized with bounding boxes. The Faster R-CNN object detection network. Semantic segmentation is the task of assigning meaning of part of an object which can be done at the pixel level by assigning each pixel to a target class such as road, car, pedestrian, sign or any number of other classes. It consists of three parts: a pre-processing network to extract high level image features, a Region Proposal Network (RPN) that produces region proposals, and a Faster-RCNN head which fine-tunes each region proposal. I would like to consider the KITTI dataset for training semantic segmentation by replicating the features of the paper “Deep Multi-modal object detection and semantic segmentation for autonomous driving: datasets, methods and challenges”
## Frameworks and Packages: 
- Python3
- NumPy
- TensorFlow > 10
- SciPy
- Dataset: KITTI

[Reference](https://scholar.google.de/scholar?q=Deep+Multi-modal+Object+Detection+and+Semantic+Segmentation+for+Autonomous+Driving:+Datasets,+Methods,+and+Challenges&hl=en&as_sdt=0&as_vis=1&oi=scholart)
