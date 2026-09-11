# Industrial Cigarette Packaging Classification & Defect Analysis

An end-to-end computer vision benchmark evaluating 10 deep learning architectures for quality inspection and defect classification across an industrial dataset of 35,000 cigarette packaging images.

## Evaluated Architectures

| Category | Models |
| :--- | :--- |
| **Classical / Baselines** | Custom CNN, AlexNet |
| **Residual & Efficient CNNs** | ResNet50, MobileNetV2, EfficientNetV2B0 |
| **Vision Transformers & SSMs** | Swin Transformer, MambaVision |
| **Real-Time Detectors (Cls)** | YOLOv8-cls |

## Dataset Overview
- **Scale:** 35,000 high-resolution industrial packaging inspection images
- **Domain:** Defect detection, surface anomaly recognition, and packaging integrity verification
- **Evaluation Metrics:** Top-1 Accuracy, Precision, Recall, F1-Score, Parameter Count, and Inference Latency (ms)
