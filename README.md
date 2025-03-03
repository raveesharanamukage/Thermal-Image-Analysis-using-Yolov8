# Thermal Image-Based Fault Detection and Localization
This repository contains a deep learning-based computer vision model for detecting and localizing faults in electrical components using thermal images. The project leverages YOLOv8 for real-time fault detection, enhancing preventive maintenance and operational safety in electrical systems.

## Features
**Automated Fault Detection:** Identifies and classifies faults like overloaded circuits, connectivity issues, deteriorated insulation, phase imbalance, and faulty circuit breakers.
**Deep Learning Model:** Uses YOLOv8 for high-accuracy fault localization.
**Dataset & Augmentation:** Includes over 1,600 annotated thermal images with preprocessing and augmentation.
**Performance Optimization:** Achieves 70.0% mAP@50, ensuring reliable fault detection.
**Standards Compliance:** Based on IEC 61439-1, IEC 60502, and IEC 62271 for temperature and safety guidelines.
**Scalability & Future Expansion:** Designed for integration with high-voltage systems and real-time monitoring solutions.

## Dataset & Model Training
**Collected 1,000+** IR images from electrical panels.
**Preprocessed & annotated** data using Roboflow.
**Trained YOLOv8** on **Google Colab with PyTorch**, optimizing detection accuracy.
## Results
> Precision: 72.8%
> Recall: 79.3%
> mAP@50: 81.1%
> Challenges: Lower accuracy in rare faults due to dataset imbalance.
## Future Enhancements
Expand dataset to include high-voltage systems.
Improve detection of rare faults using advanced augmentation.
Integrate with AI-driven predictive maintenance systems.
## Links
📂 Dataset: Google Drive Link
📜 Code & Training: Google Colab Link
