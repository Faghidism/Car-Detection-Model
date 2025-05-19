
# Image Processing Course Project - Vehicle Type Classification and Counting


## Used Custom Dataset : https://drive.google.com/drive/folders/1jDisvlDClmXu0Va1LBhqfvDN4TUYpOAq?usp=sharing

## Input & Output Videos : https://drive.google.com/drive/folders/1N1ui-NpBu9lG8rKt8SWwYMQanxJ4msu5?usp=sharing

## Implementation with Python : https://drive.google.com/drive/folders/1oSqjIiporZaDhF_FiZve8ibpzmgssCSu?usp=sharing



## Project Title  
**Real-time Vehicle Classification and Traffic Counting System**  

## Project Overview  
This project focuses on developing a computer vision system for:  
- **Vehicle detection** in traffic scenes  
- **Classification** of vehicle types (cars, trucks, buses, motorcycles, etc.)  
- **Real-time counting** of vehicles on roads  

## Key Objectives  
1. Implement an accurate vehicle detection system  
2. Classify vehicles into predefined categories  
3. Count vehicles in real-time video streams  
4. Generate traffic statistics and analytics  

## Technical Approach  

### 1. Dataset Preparation  
- Primary datasets:  
  - [Cars Image Dataset](https://www.kaggle.com/datasets/kshitij192/cars-image-dataset)  
  - [Iran Vehicle Plate Dataset](https://www.kaggle.com/datasets/samyarr/iranvehicleplatedataset/data)  
- Data augmentation techniques  
- Image quality enhancement (de-hazing, noise reduction)  

### 2. Methodology  
- **Deep Learning Approach**:  
  - Implementation using YOLOv8 (latest version)  
  - Alternative: Faster R-CNN or SSD  
- **Traditional Computer Vision**:  
  - Background subtraction for vehicle detection  
  - Feature extraction for classification  

### 3. Evaluation Metrics  
- Precision, Recall, F1-Score  
- Average Precision (AP)  
- PR (Precision-Recall) curves  
- Frame-per-second (FPS) rate for real-time performance  

## Implementation Requirements  

### Core Features  
- Real-time processing capability  
- Vehicle type classification  
- Traffic counting functionality  
- Visualization of results (bounding boxes, counters)  

### Bonus Features (Extra Credit)  
- Environmental factor removal (fog, dust, etc.)  
- License plate recognition (using Iran dataset)  
- Traffic flow analysis  
- Implementation of advanced YOLO versions  

## Technical Specifications  

### Tools and Libraries  
- **Primary Libraries**:  
  - OpenCV for image processing  
  - PyTorch/TensorFlow for deep learning  
  - Scikit-learn for traditional ML (if applicable)  
- **Development Environment**:  
  - Google Colab (for GPU acceleration)  
  - Local development with Python 3.x  

### Deliverables  
1. Complete source code with documentation  
2. Trained model weights  
3. Evaluation results on test datasets  
4. Demonstration video of system operation  

## Project Constraints  
- Maximum team size: 3 members  
- Code must be well-commented and readable  
- Individual understanding required during defense  
- Real-time performance expected (>15 FPS)  

## Expected Outcomes  
- Functional vehicle classification system  
- Accurate traffic counting mechanism  
- Comprehensive evaluation report  
- Potential for integration with ITS (Intelligent Transportation Systems)  

**Note**: The best implementation (based on evaluation metrics) will receive top marks in the course.
