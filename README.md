# 🐾 WildAI – AI-Powered Wildlife Monitoring & Human-Wildlife Conflict Prevention System

WildAI is an AI-powered wildlife monitoring and early-warning platform designed to detect wildlife in real time, monitor animal movement, assess potential human-wildlife conflict risks, and provide timely alerts. The system combines computer vision, object tracking, geospatial analysis, and live camera monitoring to improve wildlife surveillance and support human safety.

## 🌍 Project Overview

Human-wildlife conflict is a growing concern, particularly in areas where human settlements overlap with wildlife habitats. Traditional monitoring methods often depend on manual observation and delayed reporting.

WildAI addresses this challenge through an integrated platform that processes live camera feeds, identifies wildlife and human presence, tracks detected objects, and provides automated alerts when potential threats are identified.

## ✨ Key Features

* Real-Time Wildlife Detection: Detects wildlife and humans from live camera feeds using YOLO11 Nano.
* Object Tracking: Uses ByteTrack to track detected objects across consecutive video frames.
* Live Camera Monitoring: Supports IP Webcam, ESP32-CAM, and compatible camera streams.
* Low-Light Image Enhancement: Uses CLAHE to improve image visibility under poor lighting conditions.
* Geospatial Risk Analysis: Uses geospatial technologies to analyze wildlife sightings and identify potential risk zones.
* Safe Destination Identification: Helps identify safer destinations based on spatial risk information.
* Automated SMS Alerts: Sends notifications when potential wildlife threats are detected.
* Wildlife Sighting Submission: Allows users to upload wildlife images and submit sighting information.
* Web-Based Dashboard: Provides a centralized interface for monitoring detections, alerts, and wildlife activity.

 ## 🧠 AI Models & Algorithms

Technology	Purpose
YOLO11 Nano	Real-time wildlife and human detection
ByteTrack	Multi-object tracking across video frames
CLAHE	Low-light image enhancement
Geospatial Analysis	Spatial risk assessment and safe-destination identification

## 🏗️ System Architecture

WildAI follows a modular architecture consisting of the following layers:

1. Data Acquisition Layer: Collects live video feeds from IP cameras, ESP32-CAM modules, and smartphones. Also accepts user-submitted wildlife images and sighting information.
2. AI Processing Layer: Processes video frames using YOLO11 Nano for object detection, CLAHE for image enhancement, and ByteTrack for object tracking.
3. Spatial Analysis Layer: Processes wildlife sighting locations and performs geospatial risk analysis to identify potential conflict zones.
4. Alert Management Layer: Generates automated SMS notifications based on detected threats and system-defined alert conditions.
5. Application Layer: Provides a web dashboard for administrators and users to access monitoring information, submit sightings, and view relevant alerts.

## 🛠️ Technology Stack

Frontend

* React.js
* HTML5
* CSS3
* JavaScript

Backend

* Python
* Flask
* REST APIs

Artificial Intelligence & Computer Vision

* YOLO11 Nano
* ByteTrack
* OpenCV
* CLAHE

Camera & Video Streaming

* IP Webcam
* ESP32-CAM
* RTSP
* WebRTC

Geospatial Technologies

* Geospatial data processing
* Spatial risk analysis
* Mapping and location-based analysis

Database & Notifications

* [Add your actual database technology]
* SMS Gateway / API integration

AI-Assisted Development

* Claude
* Cursor
* AI coding agents

## ⚙️ Working Methodology

1. Camera devices capture live video footage from monitored locations.
2. Video frames are extracted and passed to the AI processing pipeline.
3. YOLO11 Nano detects wildlife and human presence.
4. ByteTrack maintains object identities across video frames.
5. CLAHE enhances images when low-light conditions affect visibility.
6. Detection and sighting location information is used for geospatial risk analysis.
7. The system generates relevant alerts and sends SMS notifications.
8. Users can submit wildlife sightings through the web application, while administrators can monitor detections and system activity through the dashboard.

🚀 Installation & Setup

Prerequisites

* Python 3.10+
* Node.js and npm
* Git
* Camera device or compatible IP camera application

1. Clone the Repository

git clone <YOUR_GITHUB_REPOSITORY_URL>
cd WildAI

2. Backend Setup

cd backend
python -m venv venv

Activate the virtual environment:

Windows

venv\Scripts\activate

Linux / macOS

source venv/bin/activate

Install dependencies:

pip install -r requirements.txt

Start the backend server:

python app.py

3. Frontend Setup

Open a new terminal:

cd frontend
npm install
npm run dev

4. Camera Configuration

* Connect your smartphone and computer to the same local network when using IP Webcam.
* Start the IP Webcam application on your smartphone.
* Copy the camera stream URL.
* Configure the stream URL in the WildAI dashboard.
* Ensure that the backend can access the camera stream.

Note: Camera accessibility depends on the network configuration. Private IP camera addresses generally work only when the backend can reach the same local network or through an appropriately configured network tunnel.

## 📌 Project Objectives

* Improve real-time wildlife surveillance.
* Reduce delays in identifying potential human-wildlife conflicts.
* Enable location-based wildlife risk assessment.
* Provide timely alerts to support preventive action.
* Build an integrated and scalable wildlife monitoring platform.

## 🔮 Future Enhancements

* Integration of additional IoT camera devices.
* Improved wildlife species classification.
* Advanced animal behaviour analysis.
* Predictive wildlife movement analysis.
* Cloud-based video processing and storage.
* Wider deployment across wildlife-sensitive regions.

## 👥 Project Information

Project Name: WildAI

Domain: Artificial Intelligence, Computer Vision, IoT, Geospatial Technology

Project Type: Academic / Engineering Project

Objective: AI-powered wildlife monitoring and human-wildlife conflict prevention.

⸻

  

*Protecting Lives, Preserving Wildlife.*
