# Full-Stack ANPR System with Camera Calibration

## Overview
A complete end-to-end ANPR solution developed for physical deployment at real sites, focusing on accurate camera calibration and automated vehicle identification.

## Objectives
- Create a robust ANPR pipeline for parking/security systems  
- Improve recognition accuracy through calibration  

## Technologies
- **Raspberry Pi** for on-site deployment  
- **YOLO + ONNX Runtime** for detection  
- **SQL** for results storage  
- **Python scripts** for automation  

## Key Implementations
- Camera calibration and distortion correction for site-specific conditions.  
- Real-time inference pipeline integrated with databases.  
- APIs for recognition results.  

## Challenges & Solutions
- Environmental issues (lighting, angles) → corrected with calibration scripts.  
- Achieved stable real-time inference despite hardware constraints.  

## Outcomes
- Successfully deployed at a physical site.  
- Automated vehicle tracking enabled.  

## Screenshots
![Camera open during calibration setup](camera_setup.png)  
![Deployed ANPR model running on-site](deployed_anpr_system.png)  
![Recognition output from deployed site](anpr_output_site.png)  
