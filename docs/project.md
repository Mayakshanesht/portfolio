# AI Engineer Portfolio

Welcome to my project portfolio! Below is a collection of projects I’ve worked on, showcasing my expertise in AI, machine learning, and autonomous systems. These projects range from object detection and 3D reconstruction to semantic segmentation and CI/CD pipeline implementations. Explore the repositories to get a glimpse of my skills in action.

---

## Project List

## I. Physical AI

### 1.  **Synthetic Scenario Generation for training VLA/RL/IL Model for Robotic Arm Manipulation**
- **Description**: Developed the Synthetic Scenario generation pipeline to generate 4D physics Accurate scenario file in USD format to generate the dataset to train the Robotic Foundation Models. 

### 2.  **Fine Tuned Groot N 1.5 on LeRobot dataset and deployed on SO101 arm for simple Pick-place task**
- **Description**:
1. Setup the Environment
2. Finetuned the Groot N 1.5 with demonstrations present in the LeRobot Dataset
3. Running and Evaluating the Performace for simple pick-place tasks.


## II. Autonomous Driving

## A. Traditional ML and Deep learning Based Projects

### 3. **Colab Notebook to practice basic Unsupervised and Supervised Algorithms**
- **Description**: A short notebook where I practiced various Unsupervised and Supervised learning Algorithms Implementation and Understood it's working principles. 
- **Colab Link**: [Unspervised and Supervised Algo Practice](https://colab.research.google.com/drive/1-PU8ZK6OrKEFSLTnsHajmIk6fJNqHHu2?usp=sharing&authuser=0)


### 4. **Machine Learning Based AEB Project with MetaDrive Simulator**
- **Description**: This notebook records a dataset for  using MetaDrive, trains both  (Brake flag) and  (Brake value) ML models, evaluates them, and visualizes model predictions in Colab.
Collect dataset from MetaDrive simulation (ego speed, rel speed, distance, brake_flag, brake_value).Train multiple classification models and regression models.Evaluate models with metrics (classification report, confusion matrix, regression R²/MSE).Visualize predictions from trained models.
- **GitHub Repo**: [Automated AEB braking with ML algorithms](https://github.com/Mayakshanesht/ml-based-aeb.git)


### 5. **Battery Parameter Prediction Using DNN**
- **Description**: **Deep Neural Networks (DNN/RNN)** for battery parameter prediction in energy applications.
- **GitHub Repo**: [BatteryParameterPrediction_Regression_DNN](https://github.com/Mayakshanesht/Machine_learning_practice/blob/main/BatteryParameterPrediction_Regression_DNN.ipynb)


## B. Generative Models - VAE, GAN and Diffusion Models

### 6. **Autonomous Driving Scene Generation with ControlNet-Guided Diffusion**
- **Description**: This project demonstrates how ControlNet enables structured text-to-image generation using depth and segmentation maps, applied to autonomous driving datasets. We will:

Generate synthetic driving scenes with realistic road geometry.
Compare ControlNet-guided vs unconditioned diffusion.
Create a small synthetic dataset for ADAS model training.
- **GitHub Repo**: [Autonomous_Driving_Scene_Generation_with_Stable_diffusion_controlnet_and_domain_adaptation_with_controlnet_finetuning](https://colab.research.google.com/drive/18HoqZ7VICtxpDnJsbNh5td-PlshGV9yp?usp=sharing)

### 7. **CNN-Based Classification & GAN Projects**
- **Description**: Various **CNN**-based projects for **object detection**, **face detection**, and **GAN** applications.
- **GitHub Repo**: [Autonomous_Driving_Lecture_Resources](https://github.com/Mayakshanesht/Autonomous_Driving_Lecture_resources/tree/Perception)


## C. Perception and Deep Learning

## a. Object Detection & TRacking Projects

### 8. **Object Detection & Multi-Object Tracking**
- **Description**: Multi-object tracking using **YOLOv3** and **DeepSort** in real-time scenarios.
- **GitHub Repo**: [Multi_Object_Tracker_YOLOv3](https://github.com/Mayakshanesht/objrct_tracking_new/blob/main/Multi_object_tracker_yolov3_version3.ipynb)

### 9.**3D Object Detection (Traditional Methods)**
- **Description**: Traditional methods of 3D object detection using **RANSAC**, **DBSCAN**, and **PCA**.
- **GitHub Repo**: [3DLidar_ObjectDetection_Ransac_DBSCAN_PCA](https://github.com/Mayakshanesht/3DLidar_ObjectDetection_Ransac_DBSCAN_PCA)

### 10. **Object Detection and Tracking using Kalman Filters**
- **Description**: Real-time object tracking using **Kalman Filters** integrated with **YOLOv3** for efficient tracking.
- **GitHub Repo**: [Bicycle_Tracking_Project](https://github.com/Mayakshanesht/Bicycle_Tracking_project)

### 11. **3D Deep Learning with PointNet Architecture**
- **Description**: Implementation of **PointNet** for 3D object classification and segmentation.
- **GitHub Repo**: [PointNet_3D_Deep_Learning](https://github.com/Mayakshanesht/3d-deep-learning/blob/main/PointNet.ipynb)

## b. Segmentation Project

### 12. **Semantic Segmentation for Drivable Area Detection**
- **Description**: Deep learning approach to detect drivable areas using **semantic segmentation**.
- **GitHub Repo**: [Semantic-Segmentation](https://github.com/Mayakshanesht/Semantic-Segmentation)

## c. Stereo Vision and 3D Reconstruction

### 13. **Depth Estimation, Stereo Vision and 3D Reconstruction**
- **Description**: 3D reconstruction from stereo vision using deep learning techniques.
- **GitHub Repo**: [Stereo_Vision](https://github.com/Mayakshanesht/Stereo_Vision)


## d. Localization, SLAM and Bird's Eye View Generation 

### 14. **Point Cloud Registration, SLAM and ROS2 implementation**
- **Description**: Executed projects on lidar-camera calibration, multi-lidar registration (using GICP+ICP), and deep learning-based sensor fusion.    Designed tutorials on perception systems, SLAM, and 3D deep learning.
- **GitHub Repo**: [Multi-LiDAR Registration](https://github.com/Mayakshanesht/multi_lidars_calibration.git)

### 15. **PELR Transformer for BEV Semantic Grip Mapping**
- **Description**: Research on the **PELR Transformer** for **BEV semantic grip mapping** in autonomous vehicles.
- **GitHub Repo**: [BEV Perception](https://github.com/Mayakshanesht/bev_perception_research_project.git)
- **Google Colab**: [BEV Perception](https://colab.research.google.com/drive/1VWsqo5fT3SS6SZL7Xf2Y1ZdM53xZ9Nax?usp=sharing)
- **PPT**:[PELR Transformer Project](https://www.canva.com/design/DAFttO36_lw/5KLLUknyPWy0QMGtdd8hiw/edit?utm_content=DAFttO36_lw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## D. Controls Projects

### 16. **Permanent Magnet Synchronous Motor Modeling and Field Weakening (PMSM) Control**
- **Description**: PMSM motor modelling and control with field weakning.
- **GitHub Repo**: [PMSM Model and Control](https://github.com/Mayakshanesht/pmsm_control_field_weakning.git)

### 17. **Adaptive Cruise Control (PID)**
- **Description**: Implement a PID-based Adaptive Cruise Controller to maintain safe distance and smooth throttle control.
- **GitHub Repo**: [Adaptive Cruise Control (PID)](https://github.com/Mayakshanesht/adaptive_cruise_control_pid.git)

### 18. **Electronic Stability / Traction Control (LQR)**
- **Description**: Design a Linear Quadratic Regulator to stabilize yaw and regulate traction under varying road friction.
- **GitHub Repo**: [Electronic Stability / Traction Control (LQR)](https://github.com/Mayakshanesht/electronic_stability_control_lqr.git)

### 19. **Trajectory Planning & Control (MPC)**
- **Description**: Implement a Model Predictive Controller for trajectory tracking with smooth steering, obstacle avoidance, and minimal jerk.
- **GitHub Repo**: [Trajectory Planning & Control (MPC)](https://github.com/Mayakshanesht/Trajectory_planning_control.git)


## E. ROS Projects

### 20. **Object Detection with ROS Package**
- **Description**: ROS-based object detection and tracking for autonomous vehicles.
- **GitHub Repo**: [ROS Package](https://github.com/Mayakshanesht/ROS)


## F. Continuous Integration and Continuous Deployment

### 21. **CI/CD Project**
- **Description**: A complete CI/CD pipeline demonstration for automating builds and deployments.
- **GitHub Repo**: [ci_cd_demo](https://github.com/Mayakshanesht/ci_cd_demo.git)



## G. Advanced C++ 

### 22. **Advanced C++ Practice for Autonomous Systems**
- **Description**: A collection of advanced **C++** programming techniques for autonomous system development.
- **GitHub Repo**: [Advanced_CPP_Practice](https://github.com/Mayakshanesht/advanced_cpp_practice)

## H. Teaching 

### 23. **YouTube Channel on Autonomous Driving**
- **Description**: A **YouTube channel** dedicated to teaching **autonomous driving** concepts and applications.
- **Channel Link**: [Robotics & Autonomous Vehicles](https://www.youtube.com/@roboticsandautonomousvehic1343/videos)

### 24. **AI Bootcamp — ML → LLMs → Generative AI**
- **Description**: Learn machine learning, deep learning, reinforcement learning, and generative AI for robotics and autonomous systems. Includes 5 recruiter-ready projects and portfolio deliverables.
- **Channel Link**: [AI Bootcamp](https://sites.google.com/view/cloudbee-robotics-courses/courses/ai-bootcamp)

### 25. **ADAS & Autonomous Driving Bootcamp**
- **Description**: Learn system design, safety (ISO 26262/SOTIF), simulation, and validation for advanced driver assistance systems. Includes lane keeping, fusion, and real-world testing workflows.
- **Channel Link**: [ADAS & Autonomous Driving Bootcamp](https://sites.google.com/view/cloudbee-robotics-courses/courses/advanced-driver-assistance-systems-development-bootcamp)


### 26. **Modern Vehicle Control Bootcamp — PID → LQR → MPC**
- **Description**: Master modern vehicle control techniques for autonomous driving. Learn Linear, Stochastic, and Optimal Control and apply them in real projects like ACC, ESC, and MPC-based trajectory tracking.
- **Channel Link**: [Modern Vehicle Control Bootcamp — PID → LQR → MPC](https://sites.google.com/view/cloudbee-robotics-courses/courses/advanced-controls-bootcamp-for-autonomous-driving)

### 27. **CI/CD for Autonomous Systems — Jenkins · Docker · Kubernetes**
- **Description**: Learn to automate builds, tests, and deployments for AI and Control projects using GitHub, Jenkins, Docker, and Kubernetes. Build a full DevOps pipeline and deploy a live app to Kubernetes.
- **Channel Link**: [CI/CD for Autonomous Systems — Jenkins · Docker · Kubernetes](https://sites.google.com/view/cloudbee-robotics-courses/courses/ci-cd-for-autonomous-systems)


### Continued...


---

## Additional Information

In addition to these projects, I have published several **research papers** and actively contribute to projects involving **autonomous vehicles**, **robotics**, and **AI/ML**. My aim is to create robust, scalable solutions and build next-generation technologies.

Feel free to explore the repositories and reach out if you'd like to collaborate or discuss any of these projects!
