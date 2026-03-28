
# 🌲 Illegal Logging Detection using Object Detection (YOLOv8)

## 📌 Project Overview

This project detects illegal logging activities using **object detection techniques** applied to **satellite imagery**. A YOLOv8 deep learning model is trained to identify logging patches within forested landscapes, enabling automated monitoring of deforestation and forest degradation.

Synthetic Planet-like imagery is used to simulate real-world conditions for training and testing.

---

## 🎯 Objectives

* Generate synthetic satellite imagery representing forest landscapes
* Simulate illegal logging patches
* Create bounding box annotations in YOLO format
* Train a YOLOv8 object detection model
* Detect and visualize illegal logging areas

---

## 🛰 Data Description (Synthetic)

* High-resolution satellite-like images (Planet-style)
* Forest background with green spectral characteristics
* Logging areas represented as cleared/bare patches

---

## 🤖 Model Architecture

* **YOLOv8 (Ultralytics)**
* Real-time object detection model
* Detects logging areas using bounding boxes

### Class Labels:

| Class ID | Label   |
| -------- | ------- |
| 0        | Logging |

---

## ⚙️ Workflow

1. Generate synthetic dataset
2. Create YOLO annotation files
3. Configure dataset using YAML
4. Train YOLOv8 model
5. Run inference on sample images
6. Visualize detected logging areas

---

## 📊 Outputs

* Trained YOLO model weights
* Detection results with bounding boxes
* Sample prediction visualizations

---

## ⚙️ Requirements

Install dependencies:

```bash
pip install ultralytics opencv-python numpy matplotlib
```

---

## 🚀 How to Run

```bash
python illegal_logging_detection_yolo.py
```

---

## 🌍 Applications

* Illegal logging monitoring
* Forest conservation enforcement
* Deforestation tracking
* Environmental compliance monitoring
* Sustainable forest management

---

## 🔬 Future Improvements

* Use real PlanetScope or Sentinel-2 imagery
* Increase dataset size and diversity
* Add multi-class detection (roads, settlements, fires)
* Integrate temporal change detection
* Apply transfer learning for higher accuracy

---

## 📜 License

This project uses synthetic data and is intended for educational, research, and personal development purposes.


