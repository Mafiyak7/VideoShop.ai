

# 🛒 AmoCart.ai

AmoCart.ai is an AI-powered visual shopping assistant that combines **YOLOv8 object detection** and **image similarity matching** to enable intuitive, image-based product discovery. This project showcases full-stack skills in computer vision, model training, and Python app integration, designed for modern e-commerce experiences.

---

## 🚀 Features

- 🔍 Real-time object detection using **YOLOv8 (Ultralytics)**
- 🖼️ Image similarity matching for product recommendations
- 🛠️ End-to-end system: model training → detection → recommendation
- 🧠 Deep learning and computer vision integration
- 🖥️ User-friendly interface built in Python (Streamlit or Flask)
- 🧪 Easily extendable for any custom dataset

---

## 📂 Project Structure

```bash
AmoCart.ai/
├── app.py                  # Main application file
├── train_model.py          # Training script for YOLOv8 model
├── image_similarity.py     # Image feature extraction & similarity logic
├── yolo_check.py           # Script to verify YOLOv8 model functionality
├── hower_object.py         # Object interaction/detection logic (hover/spatial)
├── yolov8n.pt              # Pre-trained YOLOv8 nano model
├── requirement.txt         # Python dependencies
├── README.md               # Project documentation
└── LICENSE
