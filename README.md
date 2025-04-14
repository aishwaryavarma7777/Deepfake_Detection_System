# Deepfake_Detection_System

This project presents a robust deepfake image detection system that combines the strengths of ResNet50 and Feature Pyramid Networks (FPN) to identify manipulated digital media. As deepfake technologies grow more sophisticated, traditional detection approaches fall short. Our proposed dual-architecture framework extracts hierarchical features and analyzes images at multiple scales, enabling precise detection of subtle and large-scale anomalies.

Key highlights:

Utilizes ResNet50 for deep feature extraction and FPN for multi-scale analysis.

Trained on the OpenForensics dataset using a custom preprocessing pipeline (resizing, normalization, data augmentation).

Achieved 93.09% accuracy, 90.13% recall, and 0.9856 ROC-AUC score.

Features a Gradio-powered GUI allowing users to upload images and detect whether they are real or fake in real time.

Potential applications include social media monitoring, digital forensics, and public misinformation detection.

This work contributes toward building a more trustworthy digital ecosystem by addressing the rising challenge of deepfake content with AI-driven forensics.

Code: Deepfake_Detection_Code
Data Folder: Dataset

Deployment: https://huggingface.co/spaces/Maddy2911/deepfake-detector
