# Smart Face Recognition Alert System

## 🚀 Overview
A real-time AI-powered face recognition system that detects known and unknown individuals using a webcam feed. The system triggers instant alerts for intruders, sends notifications via Telegram, activates a loud alarm, and supports dynamic learning by adding new faces to the database. It also includes optional face mask detection using MobileNetV2.

---

## 🧠 Key Features
- Real-time face detection and recognition
- Classification of individuals as **Known / Unknown**
- Instant Telegram alerts with captured image
- Loud alarm trigger for unknown intruders
- Add new faces dynamically without retraining model
- Optional face mask detection using MobileNetV2
- Local database storage for face encodings

---

## ⚙️ Tech Stack
- Python
- OpenCV
- face_recognition (dlib)
- NumPy
- TensorFlow / Keras (MobileNetV2 for mask detection)
- Telegram Bot API

---

## 📌 How It Works
1. Webcam captures live video feed  
2. Faces are detected and encoded  
3. Encoded faces are compared with known database  
4. If match found → "Known Person" displayed  
5. If no match → "Unknown Intruder" detected  
6. Telegram alert + image sent instantly  
7. Alarm sound triggered for security warning  
8. New faces can be added dynamically to dataset  

---

## 📷 Outputs
- Real-time bounding box with name labels  
- Telegram notification with image  
- Audio alarm for unknown detection  

---

## 🔐 Use Case
- Home security systems  
- Office access monitoring  
- Restricted area surveillance  
- Smart attendance systems  

---

## 📈 Future Improvements
- Cloud database integration  
- Mobile app for alerts  
- Improved face recognition accuracy using deep learning models  
- Multi-camera support  

---

## 👨‍💻 Author
Dalai Sai Deepika
BTech Student | AI & Full Stack Developer
