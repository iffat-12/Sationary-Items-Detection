## **Vision-Based Billing System for Stationery Items**

### **Introduction**
This project aims to implement a vision-based billing system for stationery items purchased in a shop. The system is designed to detect various combinations of stationery items, count them, and display a formatted bill with assumed prices for each item. The implementation is divided into several steps, including data collection and labeling, model training, and model testing for both images and videos.

### **Step 1: Data Collection and Labeling**
**Data Collection:**
Collected a dataset of at least 1200 images of stationery items such as books, notebooks, erasers, scales, pencils, sharpeners, ballpoints, pointers, etc.
Ensuring the images are diverse and cover different combinations of items.

**Labeling:**
Use RoboFlow annotation tool for labeling items in images.
Classes for the model are books, notebooks, erasers, scales, pencils, sharpeners, ballpoints, pointers, etc.

### **Step 2: Model Training**
**Model Selection:**
We choose YOLOv5 (version 5) model for our vision based system

**Training:**
Train the chosen model on the labeled dataset. Use a pre-trained model and fine-tune it on the dataset or train a model from scratch. Evaluate the model's performance on the validation set and adjust hyperparameters as needed.
**Split the dataset:** 75% for training, 15% for validation, and 10% for testing.

### **Step 3: Model Testing**
Image Testing:
Count the detected items and display a formatted bill with assumed prices for each item.
Video Testing:
Implement functionality for video input where the program processes each frame, annotates the bill on top, and outputs the annotated video.
Tools and Technologies
Dataset Generation and Annotations: **Roboflow**
Object Detection Model: **YOLOv5**
[Dataset Link]([https://www.example.com/dataset](https://app.roboflow.com/national-university-fast/stationary-items-dataset))
