

## AI-Powered Burnt and Unburnt Cookie Detection

This repository contains the end-to-end implementation of an **AI-based food quality inspection system** developed for **Rakusen**, a UK-based food manufacturing company.  
The system detects **burnt and unburnt cookies** in real time using **computer vision**, **deep learning**, and **data engineering**.

---

## Project Overview

Food quality control in industrial environments requires **precision, consistency, and reliability**.  
Traditional inspection methods struggle to maintain efficiency at production scale.  

To address this, we developed a **fully automated detection pipeline** powered by **YOLOv8** and **Convolutional Neural Networks (CNNs)**, integrated through a **Flask API backend** and a **React dashboard frontend**.  
The system operates in **real time**, streaming data from **Basler industrial cameras** on the production floor, with high fault tolerance and GPU-accelerated training.

---

## Key Features

-  **Real-Time Detection:** Provides instant quality control feedback on the production line.  
-  **Deep Learning Models:** Custom-trained **YOLOv8** and **CNN** architectures for object detection and classification.  
-  **Custom Data Pipeline:** Built specifically for the food industry with robust fault tolerance, remote data collection, and GPU computing integration.  
-  **Data Labelling:** Manually labeled using **LabelImg** and **CVAT** for pixel-accurate annotation.  
-  **Data Preprocessing:** Includes automated data cleaning, augmentation, and normalization.  
-  **Industrial Camera Integration:** Utilized **Basler Cameras** for high-resolution, real-time image capture.  
-  **Full Deployment Stack:**  
  - **Backend:** Flask RESTful API for model inference and orchestration  
  - **Frontend:** React.js dashboard for visualization and live monitoring  
  - **Database:** MongoDB for metadata and logs  
  - **Cloud:** AWS EC2 & S3 for scalable computation and storage  
-  **GPU-Accelerated Training:** Leveraged **CUDA-enabled GPUs** for model training and optimization.  
-  **Industrial Integration:** Designed for continuous operation in live production environments.

---

##  System Architecture
<img width="772" height="397" alt="image" src="https://github.com/user-attachments/assets/7dbbb3f6-1261-4c7a-8cbf-f445b9c3ecb1" />

<img width="689" height="430" alt="image" src="https://github.com/user-attachments/assets/92ae4ce6-d163-4b31-98ac-17318dbf52f7" />

## Model Training Details

| **Component** | **Description** |
|----------------|-----------------|
| **Framework** | PyTorch |
| **Models Used** | YOLOv8 (Object Detection), Custom CNN (Classification) |
| **Training Hardware** | NVIDIA CUDA GPU |
| **Image Resolution** | 640 × 640 px |
| **Data Source** | Real-time images from Basler Cameras |
| **Augmentation** | Rotation, Brightness, Contrast, Blur |
| **Optimizer** | Adam / SGD |
| **Loss Functions** | BCE + IoU Loss |
| **Accuracy** | 96.4% Detection, 94.8% Classification |

---

##  Tech Stack

| **Category** | **Technologies** |
|---------------|------------------|
| **Languages** | Python, JavaScript |
| **AI Frameworks** | PyTorch, Ultralytics YOLOv8 |
| **Data Pipeline** | Python, AWS S3, MQTT, MongoDB |
| **Data Labelling Tools** | LabelImg, CVAT |
| **Backend** | Flask RESTful API |
| **Frontend** | React.js, Axios |
| **Database** | MongoDB |
| **Deployment** | AWS EC2, Docker |
| **Visualization** | React.js Dashboard |
| **Cameras** | Basler Industrial Cameras |

---

