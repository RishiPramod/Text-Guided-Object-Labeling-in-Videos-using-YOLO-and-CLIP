# Text-Guided Object Labeling in Videos using YOLO and CLIP

This project uses YOLOv8 and OpenAI's CLIP model to perform text-based object labeling in videos.

## Features
- YOLOv8 for object detection
- CLIP for vision-language understanding
- Video annotation with labels from prompts

## Requirements
- PyTorch
- OpenCV
- ultralytics
- git-lfs (for large notebooks)

## Getting Started
1. Clone the repo
2. Install dependencies
3. Run `object_tracking.ipynb`

Download the file :
'https://drive.google.com/file/d/1ZXmA_DubeeDo2EELG3g7lzrwh9lhADPm/view?usp=drive_link'

Dataset :
'https://www.kaggle.com/datasets/robikscube/driving-video-with-object-tracking/data?select=bdd100k_videos_train_00'

NOTE : The visual output is not coming due to Colab’s video renderer or player not displaying the latest saved frames correctly.Try to check the downloaded ".ipynb" in Visual Studio. However, the same video runs perfectly with annotations in Visual Studio, confirming that the detection and labeling are working as expected.
