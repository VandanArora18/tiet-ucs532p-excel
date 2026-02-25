<p align="center">
  <h1 align="center">📐 AutoDimenSys</h1>

  <p align="center">
    <strong>Camera-Based Automated Object Dimension Measurement Using Classical Computer Vision</strong>
  </p>

  <p align="center">
    <a href="#-overview">Overview</a> •
    <a href="#-system-capabilities">Capabilities</a> •
    <a href="#-processing-architecture">Architecture</a> •
    <a href="#-technology-stack">Tech Stack</a> •
    <a href="#-working-methodology">Methodology</a> •
    <a href="#-performance-analysis">Evaluation</a> •
    <a href="#-constraints">Limitations</a> •
    <a href="#-future-directions">Future Scope</a>
  </p>
</p>

---

## 📘 Overview

**AutoDimenSys** is a computer vision driven measurement system developed to estimate real-world object dimensions using standard imaging devices such as webcams or smartphone cameras.

The system removes dependency on manual measuring tools and expensive industrial scanners by applying geometric analysis and reference-based calibration techniques. By detecting a known reference object placed near the target item, the system converts pixel distances into accurate physical measurements.

This solution is particularly useful for logistics validation, manufacturing inspection, retail inventory verification, and digital space organization.

---

## 🎯 Motivation

Manual inspection and measurement processes often introduce inconsistencies due to fatigue and estimation errors. Small industries and MSMEs frequently rely on human inspection for parcel sizing or product validation, which reduces efficiency during repetitive operations.

Although automated dimensioning solutions exist, they typically depend on laser sensors or specialized setups that increase operational cost. This project focuses on creating an affordable alternative capable of operating using commonly available cameras.

---

## ✨ System Capabilities

| ✅ Supported Functions | 🚫 Outside Scope |
|---|---|
| Real-world dimension estimation | 3D laser scanning |
| Reference-based calibration | Specialized depth sensors |
| Rotated object measurement | Internal structure analysis |
| Surface irregularity indication | Material composition detection |
| Area and volume approximation | Precision metrology replacement |
| Visual measurement annotation | Permanent cloud storage |

### Measurement Functions

The system enables detection and analysis of:

- Object length and width estimation
- Rotated object boundary handling
- Parcel dimension verification
- Shape consistency monitoring
- Surface deformation indication
- Measurement visualization overlays

---

## 🏗 Processing Architecture
