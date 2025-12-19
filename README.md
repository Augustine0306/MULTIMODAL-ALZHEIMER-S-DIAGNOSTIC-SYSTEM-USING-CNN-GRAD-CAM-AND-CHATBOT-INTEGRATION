# Multimodal Alzheimer’s Diagnostic System using CNN, Grad-CAM and Chatbot

## Introduction
Alzheimer’s Disease (AD) is one of the most common neurodegenerative disorders worldwide, significantly affecting memory, cognitive abilities, and daily functioning. Early and accurate diagnosis of Alzheimer’s Disease is crucial for timely medical intervention, slowing disease progression, and improving patient quality of life.

Traditional diagnostic approaches rely on clinical assessments, cognitive tests, and manual interpretation of MRI brain scans by neurologists and radiologists. These methods are time-consuming, highly dependent on expert judgment, and prone to inter-observer variability, especially during the early stages such as Mild Cognitive Impairment (MCI).

With the increasing availability of large-scale neuroimaging data, manual analysis alone is insufficient. This creates a strong need for automated, intelligent, and interpretable diagnostic systems that can assist clinicians in accurate and efficient detection.

---

## About the Project
The aim of this project is to develop an AI-driven multimodal diagnostic system capable of classifying Alzheimer’s Disease stages using MRI brain images and providing explainable predictions.

The system integrates:
- Convolutional Neural Networks (CNNs) for MRI image classification
- Explainable AI using Grad-CAM for visual interpretation
- A medical chatbot for interactive assistance

The CNN model classifies MRI images into:
- Normal
- Mild Cognitive Impairment (MCI)
- Alzheimer’s Disease

Grad-CAM highlights important brain regions influencing the model’s decisions, improving transparency and clinical trust. A Streamlit-based web application allows users to upload MRI images, visualize predictions and heatmaps, and interact with the chatbot in real time.

---

## Features

### 🔹 Dual-Module Diagnostic Architecture
Combines Alzheimer’s stage classification and explainable visualization in a single integrated system.

### 🔹 CNN-Based MRI Image Analysis
Uses deep CNN models with transfer learning to automatically learn complex spatial and structural patterns associated with Alzheimer’s progression.

### 🔹 Explainable AI using Grad-CAM
Generates heatmaps highlighting critical brain regions such as the hippocampus and cortical areas, enhancing transparency and clinician confidence.

### 🔹 Chatbot-Based Medical Assistance
Provides conversational support for understanding symptoms, diagnosis, treatment options, and AI predictions.

### 🔹 User-Friendly Web Interface
Streamlit-based interface for MRI upload, prediction display, heatmap visualization, and chatbot interaction.

---

## System Architecture
The system architecture consists of:
1. MRI Image Input
2. Image Preprocessing
3. CNN-Based Classification
4. Grad-CAM Visualization
5. Chatbot Interaction
6. Result Display via Streamlit Web Interface

---

## Hardware Requirements
- Processor: Intel Pentium Dual Core / i3 or higher (2.00 GHz or above)
- RAM: 8 GB minimum (16 GB recommended)
- Storage: Minimum 120 GB HDD / SSD
- Keyboard: 110 keys enhanced
- GPU (Optional): NVIDIA GPU with CUDA support

---

## Software Requirements
- Operating System: Windows 7 / 8 / 8.1 / 10 / 11
- Programming Language: Python 3.10 or above

### Supporting Libraries
- NumPy, Pandas, Matplotlib, Seaborn
- TensorFlow / PyTorch
- OpenCV, PIL
- Scikit-learn

---

## Technologies Used
- IDE: Visual Studio Code / Jupyter Notebook
- Framework: Streamlit
- Deep Learning: CNN (ResNet, VGG, MobileNet)
- Explainable AI: Grad-CAM
- NLP: Chatbot using LLM concepts
- Version Control: Git and GitHub

---

## Output

### Output 1 – Home Page
<img width="635" height="292" alt="image" src="https://github.com/user-attachments/assets/e5f82e81-7f04-43fe-a55c-d4870d7d0e39" />

### Result Page :
<img width="697" height="341" alt="image" src="https://github.com/user-attachments/assets/5f5f37b2-185c-40c0-abb9-a3c7240a0864" />

---

## Results and Impact
The system demonstrates strong performance in accurately classifying Alzheimer’s Disease stages from MRI images. CNN models capture complex neurological patterns, while Grad-CAM improves interpretability.

The chatbot enhances user engagement and understanding, making the system suitable for clinical decision support, patient education, and research assistance.

---

## References
1. Selvaraju, R. R., et al., *Grad-CAM: Visual Explanations from Deep Networks*, IJCV, 2020  
2. Basaia, S., et al., *Automated Classification of Alzheimer’s Disease Using MRI and Deep Learning*, NeuroImage: Clinical, 2019  
3. Qiu, H., et al., *Multimodal Deep Learning for Alzheimer’s Diagnosis*, Nature Communications, 2022
