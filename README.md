<style>
h1 {
    color: #white;
}
h2 {
    color: #white;
}
body {
    background-color: #0d1117;
    color: #c9d1d9;
}
</style>

# Design Portfolio
## Table of Contents
- ### [Professional Experience](Professional.md)
- ### [Research Experience](research.md)
- ### [Open Source Projects](opensource.md)
- ### [Tutorials](Tutorials.md)




## Projects
### [Dynamic-ECG](opensource.md#dynamic-ecg/Dynamic-ECG) : Algorithms for ECG Signal Analysis 
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github)](https://github.com/Heartbeatman/dynamic_ecg)   ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)

My Python-based library for ECG analysis, including R,P,T wave detection, Poincare analysis, wavelets-based analysis and several Visualisation features! Portability with both short ECG & Long Form Holter data. Formats such as NumPy, EDF, H5 and even Apple Watch ECG data (CSV export).


![alt text](assets/images/sample_r_plot.png)



### [CatchAF](opensource.md#CatchAF/CatchAF): Multi-Modal Atrial Fibrillation Detection Model
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)  ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)  ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)

An AF detection model that uses Dynamic-ECG for Poincare-Plot generation as the data input for a Computer Vision model. Trained on the [IRIDIA-AF](https://www.nature.com/articles/s41597-023-02621-1) dataset, the model achieved a 98% accuracy in detecting AF from ECG data. The model is available for download and use in the CatchAF repository.

![alt text](assets/images/histogram_animation.gif)



### Deep Reinforcement Learning for Cardiac CT-Fluoroscopy Registration
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)  ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)  ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)

Implemented a deep reinforcement learning model using PyTorch and deep Q network to register 6DOF cardiac CT images with fluoroscopy images. Achieved a 90% success rate in image registration, improving the accuracy of cardiac procedures. Collaborated with CHU de Bordeaux, France, and the UWA Medical Imaging Physics Group, using CARTO EP files.

![alt text](assets/images/1707211837244.jpeg)



### Real-time Arrhythmia Sagemaker Detection System
![AWS Lambda Badge](https://img.shields.io/badge/AWS%20Lambda-F90?logo=awslambda&logoColor=fff&style=flat) ![AWS Sagemaker Badge](https://img.shields.io/badge/AWS%20Sagemaker-232F3E?logo=awssagemaker&logoColor=fff&style=flat) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Tensorflow](https://img.shields.io/badge/-Tensorflow-FF6F00?style=flat&logo=tensorflow&logoColor=white) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

Developed a real-time arrhythmia detection system using AWS Sagemaker and Lambda. The system uses a deep learning model trained on the MIT-BIH dataset to detect arrhythmias in ECG data. The model is deployed on AWS Sagemaker and invoked using AWS Lambda functions. The system achieved an accuracy of 98% in detecting arrhythmias in real-time ECG data.





### Assistive Smart Orthopedic Sensor Device - SMART BOOT
![Raspberry Pi](https://img.shields.io/badge/-Raspberry%20Pi-C51A4A?style=flat&logo=Raspberry-Pi) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) 

![alt text](assets/images/pls.png)

Constructed Gait-Force frequency Algorithm Development using non-linear differential equation modeling, implemented with Python. Engaged in signal engineering & sensor design. Focused on high bandwidth data optimization. Developed a biosensor area monitoring system. CoLed the clinical prototype Development, including the regulatory & patent application process.




## Tutorials

### Train on MAC, upload to AWS Sagemaker - 10/2023
**AWS Sagemaker, Python, MacOS**

### BioSignals 




### R wave detection
**ECG, Python, NumPy**


### Phasor Transform

### Poincare plot






