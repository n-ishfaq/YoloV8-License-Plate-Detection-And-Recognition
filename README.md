# YoloV8-License-Plate-Detection-And-Recognition

## 🚗 **Project Overview**  
This project demonstrates the use of **YOLOv8** for detecting license plates from images and videos and integrates OCR for recognizing the plate numbers.  

### 🔑 **Features**  
- **Accurate Detection**: Uses YOLOv8 for license plate detection in various scenarios (e.g., moving vehicles, different lighting conditions).  
- **OCR Integration**: Employs `EasyOCR` to extract and recognize text from detected license plates.  
- **Scalable Workflow**: Handles single images, video frames, or large datasets efficiently.  

---

## 🛠️ **Setup Instructions**  

### 1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/n-ishfaq/YoloV8-License-Plate-Detection-And-Recognition
cd YoloV8-License-Plate-Detection-And-Recognition
```

### 2️⃣ **Install Dependencies**  
Ensure Python 3.8 or higher is installed. Then, run:  
```bash
pip install -r requirements.txt
```

### 3️⃣ **Download YOLOv8 Model**  
Download the pretrained YOLOv8 weights:  
```bash
yolo download model=yolov8n.pt
```

## 📂 **Project Structure**  
- `license_plate_detection.ipynb`: Main script for detection.
- `license_plate_recognition.ipynb`: For Recognition  
- `utils.py`: Helper functions for image and video preprocessing.  
- `requirements.txt`: List of dependencies.  

---

## 🔧 **Technologies Used**  
- **YOLOv8**: For object detection.  
- **EasyOCR**: For optical character recognition.  
- **OpenCV**: For handling image and video inputs.  
- **Python**: Core programming language.  

---

## 🚀 **Future Plans**  
- Add a **Streamlit UI** for an interactive interface.  
- Extend support for real-time detection using webcam feeds.  
- Enhance OCR accuracy for multilingual plates.  

---

## 🤝 **Contributions**  
Feel free to fork this repository and submit pull requests with improvements or additional features.  

---

## 📜 **License**  
This project is open-source and available under the MIT License.  

---

Let me know if you’d like to include any additional details!
