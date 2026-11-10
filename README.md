# Masked-People-Detection-Project_SdaiaAcademy
Trained an AI model using a Kaggle dataset and Roboflow to detect people wearing face masks in videos.
# Masked-People-Detection-Project_SdaiaAcademy
Trained an AI model using a Kaggle dataset and Roboflow to detect people wearing face masks in videos.
Project Overview
This project uses Roboflow to train an AI-based object detection model that identifies people wearing face masks in videos.
Problem Description
Detecting people wearing face masks manually can be time-consuming, especially in crowded areas. This project automates the detection process using AI.

## Dataset & Model Used
* Dataset: Face Mask Detection Dataset from Kaggle.
* Platform: Roboflow.
* Model: RF-DETR Small
* Task: Object Detection.
* Testing: New video footage not included in the training dataset.

## Workflow



![alt text](<صورة ١٠‏-١١‏-٢٠٢٦ في الساعة ٢.١٨ ص-1.png>)




## Results & Evaluation
The RF-DETR Small model was evaluated on the test dataset, achieving the following results:
Evaluation Metric	Result
Precision	         87.7%
Recall	             64.9%
F1-Score	         72.5%
mAP@50	             72.9%
mAP@50–95	         47.4%
The model was also tested on unseen video footage to detect people wearing face masks using bounding boxes.

## Technologies Used
- Python– Model inference and video processing.
- Kaggle – Dataset source.
- Roboflow – Dataset preparation and model training.
- RF-DETR Small – Object detection model.
- Google Colab – Running and testing the model.
- OpenCV – Processing video frames and drawing bounding boxes.
- Pandas – Exporting detection results to CSV.

## How to Run the Project
1. Open the project notebook in Google Colab.
2. Install the required libraries.
3. Upload an MP4 video.
4. Enter your Roboflow API Key.
5. Run the cells in order.
6. View and download the annotated video and detection results.

## Future Improvements
- Improve detection accuracy using a larger and more diverse dataset.
- Enhance detection performance in crowded environments.
- Optimize video processing for real-time detection.
- Improve detection under different lighting conditions and camera angles.



The code is provided in the repository files.

SDAIA Academy GitHub Repository Link(https://github.com/SDAIAAcademy)
