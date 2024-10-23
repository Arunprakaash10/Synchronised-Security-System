# Synchronized Security System (SSS)

## Overview
The Synchronized Security System (SSS) is an IoT-based project designed to provide enhanced security for residential and commercial premises. This project integrates multiple sensors and devices into a centralized system, providing real-time monitoring, detection, and alerts via an Android app.

## Features
- **Motion Detection**: Detects movement using PIR sensors and sends alerts to the system.
- **Door Security**: Utilizes fingerprint scanners and cameras to verify identity. Failed attempts trigger a photo and send an email notification.
- **Smoke Detection**: Monitors air quality and alerts users in case of fire hazards.
- **Face Recognition**: Uses machine learning algorithms to detect and recognize faces in real-time via camera footage.
- **Android App Integration**: Real-time data and alerts are available through an Android app connected to the cloud database.

## Objectives
1. Develop a security network using multiple sensors (motion, smoke, cameras, etc.).
2. Implement machine learning algorithms for face and motion detection.
3. Integrate with an Android app for real-time monitoring and alerts.
4. Provide a user-friendly and efficient security solution.

## Hardware Requirements
- Raspberry Pi 4 (8GB RAM)
- PIR Motion Sensors
- MQ2 Smoke Detector
- Fingerprint Scanner
- 1080p Cameras
- Cooling Fan for Raspberry Pi
- Necessary connectors/adapters

## Software Requirements
- Python (OpenCV, Machine Learning Libraries)
- Microsoft PowerApps (for Android app)
- Amazon Web Services (AWS) for cloud storage and database

## System Architecture
1. **Central Hub**: The Raspberry Pi acts as the central hub, running all the sensor codes and synchronizing data with the cloud.
2. **Sensors**: Devices like motion detectors, cameras, and fingerprint scanners send data to the Raspberry Pi for processing.
3. **Android App**: Users can monitor security alerts and access data through the custom-built app.
