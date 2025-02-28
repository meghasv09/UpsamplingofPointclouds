# Upsampling of Point Clouds

## 📌 Overview  
**Point Clouds** are 3D data representations captured from **LiDAR sensors, 3D scanners, or depth cameras**. They are widely used in **autonomous driving, robotics, VR/AR, and 3D object reconstruction**.  

This project explores **point cloud upsampling** using **Deep Learning architectures like PointNet and PointNet++**. The goal is to enhance the resolution of sparse point clouds, improving their quality for classification, recognition, and reconstruction tasks.  

---

## 🔍 What is Point Cloud Upsampling?  
Upsampling point clouds involves **increasing point density** while preserving object structure. This is essential for:  
- **3D Object Classification & Recognition** 📦  
- **LiDAR Data Processing for Autonomous Vehicles** 🚗  
- **Medical Imaging & 3D Reconstruction** 🏥  
- **Virtual Reality (VR) & Augmented Reality (AR)** 🎮  

**PointNet & PointNet++** are deep learning models that process raw point cloud data directly, making them effective for upsampling and classification.  

---

## 🛠 Tech Stack  
- **Programming Language:** Python 
- **Libraries & Frameworks:**  
  - **TensorFlow/PyTorch** – Deep learning framework for training PointNet  
  - **NumPy** – Efficient numerical computations  
  - **Open3D** – Processing and visualization of point clouds  
  - **Matplotlib** – 3D visualization  

---

## 🚀 Implementation  
1. **Loading the Point Cloud Data**  
   - Reads a **.ply/.pcd** file using Open3D.  

2. **Processing with PointNet/PointNet++**  
   - Extracts geometric features.  
   - Classifies objects into different categories.  
   - Upsamples point clouds using deep learning.  

3. **Visualization**  
   - Displays **before and after** upsampling results.  

---

## 📊 Results & Visualization  
![pointcloud](Upsampling-of-PointCloud/pc.png?raw=true "pc")

--- 
