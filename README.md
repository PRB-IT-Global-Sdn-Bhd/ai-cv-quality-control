# AI Solutions — Computer Vision Quality Control

> **PRB IT Global Sdn Bhd** | Custom Software for SME Engineering & Construction Clients (Malaysia)

## Overview

An **AI-powered Computer Vision Quality Control** system that uses deep learning and image analysis to automatically detect defects, non-conformances, and safety violations on construction sites and in manufacturing facilities. The system reduces reliance on manual inspection and significantly improves quality assurance outcomes.

## Key Features

| Feature | Description |
|---|---|
| Defect Detection | Automated identification of cracks, spalling, and surface defects |
| PPE Compliance | Real-time detection of missing helmets, vests, and safety gear |
| Structural Analysis | AI assessment of concrete, steel, and masonry quality |
| Progress Monitoring | Visual progress tracking via drone/CCTV image comparison |
| Anomaly Detection | Unsupervised learning for unusual site conditions |
| Report Generation | Automated QC reports with annotated images |
| Edge Deployment | Runs on-site on edge devices without cloud dependency |

## Technology Stack

- **AI/ML:** Python, PyTorch, YOLOv8, OpenCV, TensorFlow
- **Backend:** Python (FastAPI)
- **Frontend:** React.js
- **Hardware:** NVIDIA Jetson (edge), IP cameras, drones
- **Database:** PostgreSQL + AWS S3 (image storage)
- **MLOps:** MLflow, Docker

## Target Users

Quality engineers, safety officers, site managers, and QA/QC teams.

## Getting Started

```bash
git clone https://github.com/PRB-IT-Global-Sdn-Bhd/ai-cv-quality-control.git
cd ai-cv-quality-control
pip install -r requirements.txt
python detect.py --source ./sample_images
```

## Licence

Proprietary — © 2024 PRB IT Global Sdn Bhd. All rights reserved.
