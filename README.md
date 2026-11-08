# Automatic Stationery Billing System

This project focuses on developing an automatic billing system for stationery items using YOLO object detection. The system is designed to automatically identify and count stationery products from purchase images and videos using a custom-trained YOLO object detection model. The detected items are assigned predefined prices, and a formatted bill is generated based on the detected quantities. A graphical user interface (GUI) is developed to support both image-based and video-based purchase processing.

## Object Categories

The detection model covers four stationery categories:

1. Eraser
2. Scale (Ruler)
3. Pencil
4. Sharpener

## Dataset Preparation

A dataset is collected using different stationery combinations and arrangements. The images are annotated using LabelImg, with annotations saved in YOLO format.

## Model Training

A YOLO object detection model is trained using the custom-labelled stationery dataset. The trained model is used to detect and classify stationery items in new purchase images and video frames.

## Automatic Billing System

### Image-Based Billing

Load a purchase image.
Detect stationery items using the trained YOLO model.
Identify and count each detected category.
Assign predefined prices to detected items.
Calculate individual subtotals and the final bill.
Display the formatted bill.
<img width="1366" height="728" alt="output1" src="https://github.com/user-attachments/assets/e66b5658-6fa8-4201-9fdc-85816d266506" />

<img width="1366" height="728" alt="output2" src="https://github.com/user-attachments/assets/c5729f3e-fa15-4ba2-9f44-33778ee0201c" />

### Video-Based Billing

Load a purchase video.
Process individual video frames.
Detect stationery items in each frame.
Annotate billing information on the video.
Generate an annotated output video.

