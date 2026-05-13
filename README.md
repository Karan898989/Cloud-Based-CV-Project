# ☁️ Cloud-Based-CV-Project

A cloud-based computer vision project built using **Microsoft Azure AI Vision Studio** for detecting human faces in images.

This project demonstrates how cloud AI services can perform real-time image analysis without requiring local machine learning model training.

---

## 📌 Project Overview

This project uses **Azure AI Vision Studio** to:

- Detect human faces in uploaded images
- Identify face boundaries using bounding boxes
- Analyze facial attributes such as:
  - Face presence
  - Face mask detection
  - Face landmarks
  - Pose attributes

The system is fully cloud-based and runs using Azure Cognitive Services.

---

## 🚀 Features

✅ Face Detection in Images  
✅ Face Bounding Box Visualization  
✅ Face Mask Detection  
✅ JSON Output Support  
✅ Cloud Deployment using Azure  

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Microsoft Azure AI Vision Studio | Face detection and image analysis |
| Azure Cognitive Services | Cloud AI services |
| GitHub | Version control and project hosting |

---

## 📷 Project Demo

### 1. Azure Vision Studio Interface
Detect faces in uploaded images using Azure AI.

![Azure Vision Studio](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/media/overview-vision-studio.png)

---

### 2. Face Detection Output
The system detects the face and displays bounding box coordinates.

Example output:
```json
{
  "Face #1": {
    "Face mask": "No"
  }
}
```

---

## 📂 Project Structure

```bash
Cloud-Based-CV-Project/
│
├── README.md
├── LICENSE
```

---

## ⚙️ How to Run

### Step 1: Open Azure Vision Studio
Visit:

https://portal.vision.cognitive.azure.com/

### Step 2: Select Feature
Choose:

```bash
Detect faces in an image
```

### Step 3: Upload Image
Upload your own image or use sample images.

### Step 4: View Results
Check:

- Detected Attributes
- JSON Output

---

## 📊 Sample Result

Input:
- Human face image

Output:
- Face detected successfully
- Face mask: No

---

## 🔐 Cloud Benefits

Using Azure provides:

- Scalability
- High availability
- Real-time processing
- No local hardware dependency

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Cloud-based computer vision workflows
- Azure AI Vision Studio usage
- Face detection APIs
- Image analysis using AI services

---

## 📖 Future Improvements

- Emotion detection
- Age estimation
- Gender prediction
- Object detection
- Live webcam integration

---

## 👨‍💻 Author

**Karan Yadav**  
B.Tech CSE (AI & ML)  
Chandigarh University  

GitHub: https://github.com/Karan898989

---

## 📜 License

This project is licensed under the MIT License.

---
