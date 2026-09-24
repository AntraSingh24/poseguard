# PoseGuard – Driver Unwanted Pose Detection & Feedback System

## Overview

PoseGuard is an AI-powered driver monitoring system designed to detect unsafe and unwanted driving postures in real time. The system uses Computer Vision and Deep Learning techniques to analyze live video feeds, identify risky driver behaviors, and provide instant feedback to improve road safety.

The project aims to reduce accidents caused by driver distraction, fatigue, improper posture, and unsafe driving habits.

---

## Problem Statement

Many road accidents occur because drivers become distracted, drowsy, use mobile phones while driving, or adopt unsafe postures. Traditional monitoring systems often fail to provide real-time behavioral analysis.

PoseGuard addresses this challenge by continuously monitoring driver posture and generating immediate alerts whenever unsafe behavior is detected.

---

## Key Features

### Real-Time Driver Monitoring

* Live webcam/video feed analysis
* Continuous posture tracking
* Real-time behavior classification

### Unsafe Pose Detection

* Mobile phone usage while driving
* Looking away from the road
* Drowsiness or sleeping posture
* Head-down posture
* Excessive distraction
* Hands-off steering posture

### Intelligent Alert System

* Visual warnings
* Audio alerts
* Risk-level notifications
* Instant feedback mechanism

### Dashboard & Reports

* Driver activity statistics
* Safety score calculation
* Violation history
* Daily and weekly reports
* Graphical analytics

### User Authentication

* Login system
* Registration system
* Secure user management

---

## Technology Stack

### Frontend

* HTML
* CSS
* JavaScript
* Tailwind CSS

### Backend

* Python
* Flask

### Artificial Intelligence & Machine Learning

* CNN (Convolutional Neural Network)
* TensorFlow
* Keras
* OpenCV

### Database

* SQLite
* SQLAlchemy ORM

---

## System Architecture

1. Video Input Collection
2. Frame Processing using OpenCV
3. Feature Extraction
4. CNN-Based Pose Classification
5. Risk Assessment
6. Alert Generation
7. Data Storage
8. Dashboard Visualization

---

## Working Flow

### Step 1

The camera captures live video of the driver.

### Step 2

Frames are extracted and preprocessed using OpenCV.

### Step 3

The CNN model analyzes driver posture.

### Step 4

The system classifies the pose into:

* Safe Driving
* Mobile Usage
* Drowsiness
* Looking Away
* Distracted Driving
* Unsafe Posture

### Step 5

If an unsafe posture is detected:

* Alert is generated
* Event is recorded
* Risk score is updated

### Step 6

Data is stored in the database and displayed on the dashboard.

---

## Project Team

### Team Name

Kasukabe Defence Group

### Members

* Antra Singh – Project Manager
* Eshya Yadav
* Ujjawal Kanojiya
* Sumati Gaur
* Amit Singh

---

## Future Enhancements

* Edge AI Deployment
* Mobile Application Integration
* GPS Tracking
* Voice Assistant Support
* Emotion Detection
* Driver Fatigue Prediction
* Cloud Analytics Dashboard
* Fleet Management Integration
* Smart Vehicle Connectivity

---

## Applications

* Smart Transportation Systems
* Commercial Vehicle Monitoring
* Logistics & Fleet Management
* Public Transport Safety
* Personal Vehicle Safety
* AI-Based Road Safety Solutions

---

## Expected Outcome

PoseGuard helps improve road safety by detecting unsafe driver behavior in real time and providing immediate corrective feedback. The system enhances driver awareness, reduces distractions, and contributes to accident prevention through AI-driven monitoring and analytics.

**"Drive Smart, Stay Safe with PoseGuard."**
