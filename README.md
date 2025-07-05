
# 🛒 AmoCart.AI – AI-Powered Product Detection & Visual Matching System

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![YOLOv8](https://img.shields.io/badge/YOLO-v8-green.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)

AmoCart.AI is an intelligent computer vision project that leverages **YOLOv8** for real-time object detection and **image similarity algorithms** to identify and match products — simulating an AI-based shopping assistant or smart checkout cart.

---

## 🧠 Features

- 🔍 Real-time **object detection** with YOLOv8
- 🧾 Product **matching** using SIFT and cosine similarity
- 🧠 **Training pipeline** for custom product datasets
- ⚡ Lightweight and fast — runs efficiently on mid-tier GPUs
- 🛠 Modular code with clean separation of concerns

---

## 📸 Demo Preview

> Coming soon – add a GIF or sample image output here!

---

## 📦 Tech Stack

| Tech        | Purpose                            |
|-------------|------------------------------------|
| Python 3.8+ | Core language                      |
| YOLOv8      | Object detection (Ultralytics)     |
| OpenCV      | Image processing                   |
| scikit-learn| Cosine similarity comparison       |
| NumPy       | Numerical computation              |
| Flask       | (Optional) serve as RESTful API    |

---

## 🗂 Project Structure

AmoCart.AI/
├── app.py # Main execution script
├── hower_object.py # Hover detection logic
├── image_similarity.py # Image comparison logic
├── train_model.py # Model training script
├── yolov8n.pt # Pretrained YOLO model
├── yolo_check.py # YOLO detection runner
├── requirement.txt # Python dependencies
├── README.md # You're reading it!
└── LICENSE # MIT License

yaml
Copy
Edit

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/AmoCart.AI.git
cd AmoCart.AI
2. Install Dependencies
bash
Copy
Edit
pip install -r requirement.txt
3. Run Object Detection
bash
Copy
Edit
python app.py
Make sure the webcam or input image path is correctly set.

🔧 Training Your Own Model
Replace the dataset and modify train_model.py:

bash
Copy
Edit
python train_model.py
Ensure you have annotated data compatible with YOLO format.

✅ Future Enhancements
Add Streamlit-based interactive demo

Deploy API with Flask

Integrate barcode & price recognition

Auto checkout billing with UI

👨‍💻 Authors
Abhay Upadhyay – GitHub

(Previously) Arjun Yaduvanshi – @ArjunYaduvanshi02

