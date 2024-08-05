# Visual Intelligence For Road Safety: Potholes Detection Using YoloV5

## Objective
The objective of this business case is to develop an advanced Pothole Detection System leveraging image datasets. Potholes pose significant risks to road safety and infrastructure, leading to accidents, vehicle damage, and increased maintenance costs. By implementing an automated system to detect and monitor potholes, we aim to enhance road safety, reduce maintenance expenses, and contribute to overall transportation efficiency.

## Data Collection
*  Data Collected from Roboflow
* Link: https://public.roboflow.com/object-detection/pothole

## Data Information
* Total 1130 images with 1 class
* Split data with the help of the split-folder library.
* For training 465, testing 67, validation 133
* Create bounding boxes with the help of the label-img tool and makesense.ai website

  
![image](https://github.com/user-attachments/assets/3536270a-6732-4dd1-85e8-47f78035119b)

## Model Selection Training
 1. Select the YoloV5 Model 
 2. Cloning the Yolov5 files from the official Repository
 3. Changing the directory
 4. Installing the dependencies
 5. Downloading YoloV5 small model for training 
 6. Set the appropriate path in the yaml file
 7. Train the model with 640 image size , 12 batch size
 8. First train the model on 100 epochs

## Visualise Training Score 
![image](https://github.com/user-attachments/assets/f5e78186-bd41-4524-a65f-b77de80e966d)

![image](https://github.com/user-attachments/assets/f664bb50-f25c-4290-8793-d338a459c396)

![image](https://github.com/user-attachments/assets/463ee9f9-3675-4c7b-a514-09baa8c86f46)


##  Testing 
Evaluate the Model on the testing images with different angles as well as on videos
![image](https://github.com/user-attachments/assets/9df86a05-2c11-4682-b3ca-bc179192b630)

## ![image](https://github.com/user-attachments/assets/1b4275fc-fccd-43f8-b6b8-a3fdebaf2f3d)


https://github.com/user-attachments/assets/7f182678-26aa-45c1-811d-80eded33c1dd




