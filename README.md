# 📐 Automated Dimensioning System

### Camera-Based Real-World Object Measurement Using Classical Computer Vision

---

## 🔎 Quick Navigation

[About](#about) • 
[Problem](#problem) • 
[Features](#features) • 
[Architecture](#architecture) • 
[Workflow](#workflow) • 
[Tech Stack](#tech-stack) • 
[Methodology](#methodology) • 
[Evaluation](#evaluation) • 
[Limitations](#limitations) • 
[Future Scope](#future-scope) • 
[License](#license)

---

## 📘 About

The Automated Dimensioning System is a computer vision based solution designed to measure real-world object dimensions using a standard camera. The system converts pixel measurements obtained from images or live video feeds into physical units such as centimeters or millimeters.

Traditional measurement approaches depend heavily on manual tools or expensive industrial scanners. This project introduces a lightweight and affordable alternative by applying classical computer vision techniques for scale calibration, object isolation, and geometric measurement.

The system aims to provide accessible measurement automation suitable for logistics, manufacturing inspection, retail inventory management, and everyday applications.

---

## ⚠️ Problem

Accurate object measurement is essential in industries such as shipping, manufacturing, and inventory management. However, manual measurement methods are slow and often introduce inconsistencies due to human error.

Industrial dimensioning systems provide automation but require costly hardware installations and controlled environments. Small businesses and MSMEs often cannot afford such solutions.

This project addresses the need for a cost-effective measurement system capable of working with commonly available cameras while maintaining reliable accuracy.

---

## ✨ Features

- Automatic object dimension estimation
- Reference object based scale calibration
- Perspective distortion correction
- Rotated object handling
- Surface defect indication
- Area and volume estimation
- Annotated measurement visualization
- Exportable measurement reports
- Works with webcam or smartphone camera

---
## 🏗 Architecture
User Interface
↓
Image / Video Capture
↓
Reference Object Detection
↓
Scale Calibration
↓
Image Preprocessing
↓
Object Detection
↓
Measurement Extraction
↓
Defect Detection
↓
Visualization & Report Generation

---

## 🔄 Workflow

The system begins by capturing an image containing both the target object and a known reference object. After acquisition, preprocessing techniques enhance image quality and improve edge visibility.

The reference object is detected first to determine the pixel-to-real-world scale. Contour detection is then applied to isolate measurable objects within the scene. Geometric bounding techniques calculate dimensions even when objects are rotated.

Finally, measurement annotations are displayed on the image and results can be exported for documentation or inspection purposes.

---

## 🛠 Tech Stack

| Layer | Technology |
|------|------------|
| Programming Language | Python |
| Computer Vision | OpenCV |
| Numerical Computing | NumPy |
| Machine Learning | Scikit-learn |
| Interface | Streamlit / Web Interface |

---

## 🔬 Methodology

The system relies entirely on classical computer vision techniques to maintain efficiency and interpretability.

Image preprocessing includes grayscale conversion and noise reduction to improve boundary clarity. Edge detection algorithms identify object outlines, while contour filtering extracts measurable shapes.

Perspective transformation corrects angled views, ensuring accurate measurement results. Dimensions are calculated using rotated bounding box geometry derived from detected contours.

Defect detection is implemented using convex hull comparison and solidity analysis to identify deformation or structural irregularities.

---

## 📊 Evaluation

System performance is evaluated under controlled environments by comparing automated measurements with manual measurements.

Evaluation focuses on:

- Measurement accuracy
- Detection consistency
- Processing speed
- Error percentage comparison

The system targets reliable measurement performance suitable for practical deployment scenarios.

---

## ⚠️ Limitations

- Performance affected by poor lighting conditions
- Requires visible reference object
- Partial object occlusion may reduce accuracy
- Camera alignment influences measurement precision

---

## 🚀 Future Scope

Future improvements may include enhanced real-time processing, improved robustness under varying lighting conditions, and expanded spatial planning capabilities.

Potential extensions include conveyor-based inspection systems and mobile deployment for portable measurement applications.

---


## 🏗 Architecture
