# face-mask-detection
Face mask detection using YOLOv5 and Faster R-CNN

# Face Mask Detection

This project explores a deep learning-based face mask detection system for identifying whether a person is wearing a mask properly, not wearing a mask, or wearing it incorrectly.

Two object detection models, YOLOv5 and Faster R-CNN, were trained and evaluated on a labeled dataset of 853 images. The project includes data preprocessing, augmentation, model training, and model comparison using precision, recall, and mAP.

## My Contribution
I was mainly responsible for the YOLO implementation and model experimentation.

## Tech Stack
- Python
- PyTorch
- YOLOv5
- Faster R-CNN
- Computer Vision

## Results
YOLOv5 achieved the best overall performance in this project:
- Precision: 0.849
- Recall: 0.922
- mAP@0.5: 0.949
- mAP@0.5-0.95: 0.668
