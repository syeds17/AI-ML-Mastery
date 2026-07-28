# YOLOv8 Object Detection - Bald vs No Bald

## 📌 Project Overview

This project demonstrates a custom Object Detection model using **YOLOv8** to detect two classes:

- Bald
- No Bald

The model is trained on a custom annotated dataset using the YOLO annotation format and performs object detection by predicting bounding boxes, class labels, and confidence scores.

---

## 🎯 Objectives

- Learn YOLOv8 object detection workflow.
- Train a custom YOLOv8 model.
- Detect objects on unseen images.
- Visualize prediction results.
- Understand evaluation metrics generated during training.

---

## 📂 Project Structure

```
YOLO-Object-Detection/
│
├── assets/
│   └── dataset.yaml
│
├── Data/
│   └── test_Dataset/
│       ├── images/
│       │   ├── train/
│       │   ├── val/
│       │   └── test/
│       │
│       └── labels/
│           ├── train/
│           ├── val/
│           └── test/
│
├── Model/
├── output/
├── runs/
├── YOLO-Object-Detection.ipynb
├── yolov8n.pt
└── README.md
```

---

## 🛠️ Technologies Used

- Python
- YOLOv8
- Ultralytics
- OpenCV
- PyTorch
- NumPy
- Matplotlib

---

## 🚀 Workflow

1. Import required libraries
2. Load YOLOv8 model
3. Configure dataset using YAML
4. Train custom model
5. Validate trained model
6. Predict on test images
7. Visualize detection results

---

## 📊 Evaluation Metrics

The model is evaluated using:

- Precision
- Recall
- mAP@50
- mAP@50-95
- Confusion Matrix
- F1 Curve
- Precision Curve
- Recall Curve

---

## 📚 Key Learnings

- YOLOv8 object detection workflow
- Dataset annotation format
- YAML configuration
- Custom model training
- Model validation
- Object detection on unseen images
- Performance evaluation using YOLO metrics

---

## 👨‍💻 Author

**Syed Sadath**

AI & ML Enthusiast