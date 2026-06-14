# Brain Tumor Detection using YOLO

## Project Overview

This project uses the YOLO (You Only Look Once) deep learning model to detect brain tumors from MRI scan images.

The system analyzes MRI images and predicts whether a brain tumor is present or absent. It can be used as an AI-assisted diagnostic tool for medical image analysis.

---

## Features

- Brain Tumor Detection from MRI Images
- YOLO-based Object Detection Model
- High-Speed Inference
- Upload MRI Image and Get Prediction
- Tumor / No Tumor Classification
- Confidence Score Display
- Google Colab Compatible

---

## Dataset

The dataset consists of MRI brain scan images containing:

- Tumor Images
- Non-Tumor Images

Dataset Structure:

```text
dataset/
│
└── brain-tumor/
    ├── images/
    │   ├── train/
    │   └── val/
    │
    ├── labels/
    │   ├── train/
    │   └── val/
    │
    └── brain-tumor.yaml
```

---

## Technologies Used

- Python
- YOLO
- Ultralytics
- OpenCV
- Google Colab
- NumPy

---

## Model Training

The model was trained using the Ultralytics YOLO framework on MRI brain scan images.

Training includes:

- Data preprocessing
- Image annotation
- Model training
- Validation
- Prediction testing

---

## Prediction Output

### Tumor Detected

```text
Tumor Detected
Confidence: 0.90
```

### No Tumor Detected

```text
No Tumor Detected
```

---

## Project Workflow

1. Collect MRI Dataset
2. Prepare Labels and Annotations
3. Configure Dataset YAML File
4. Train YOLO Model
5. Validate Model Performance
6. Upload MRI Image
7. Predict Tumor Presence
8. Display Result with Confidence Score

---

## Results

The trained model successfully identifies:

- Brain Tumor Images
- Non-Tumor Images

and provides confidence scores for predictions.

---

## Future Improvements

- Web Application Deployment
- Real-Time Prediction System
- Support for Multiple Tumor Types
- Improved Accuracy with Larger Dataset
- Integration with Healthcare Systems

---

## Author

**Devi Vaishnavi Vallala**

Artificial Intelligence & Machine Learning Student

GitHub:
https://github.com/vallaladevivaishnavi

---

## License

This project is created for educational and research purposes.
