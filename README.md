# Stereo Depth Estimation

This project explores **stereo vision** techniques for depth estimation and 3D perception.  
It covers camera calibration, disparity map generation, depth map computation, and obstacle detection in 3D from stereo images.

---

## 📌 Features
- Camera calibration and parameter extraction  
- Disparity map creation (StereoBM, StereoSGBM)  
- Depth map computation from disparity  
- Obstacle detection and distance estimation  
- Works with KITTI dataset samples  

---

## 🚀 Project Workflow
1. **Load the Images**: Use KITTI dataset samples

2. **Create a Disparity Map**: Implement StereoBM and StereoSGBM algorithms  

3. **Get Calibration Parameters**: Extract intrinsic and extrinsic camera parameters from calibration data

4. **Convert disparity into depth using camera parameters**:     Use the formula: depth = (baseline * focal_length) / disparity

5. **Find Obstacles in 3D**:  
   - Apply obstacle detection on the depth map  
   - Estimate distance to each detected obstacle

## Video Demonstration

![Demo](output/out.gif)

