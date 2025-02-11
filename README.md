# **SignLanguageTranslator**

---
### **Contents**

- [Project Overview](#Project Overview)
- [Installation Steps](#Installation Steps)
- [Live Demo](#Live Demo)
- [Technical Workflow](#Technical Workflow)
- [Model Evaluation](#Model Evaluation)
- [Dataset Details](#Dataset Details)
- [Exploratory Models](#Exploratory Models)
- [Resources and Citations](#Resources and Citations)
---

### *Project Overview*
In this presentation, we will be showcasing a Computer Vision demo utilizing YOLOv5 applied to an American Sign Language dataset containing 26 classes. Our model is capable of recognizing signs in real-time, as well as through input images or audio, and generates bounding boxes displaying labels along with confidence scores. This interactive demonstration is implemented using Streamlit, which allows for image input and intuitive user engagement.
---

### **Installation Steps**
Clone the Repository:

bash

git clone https://github.com/tanu0009/SignLanguageTranslator.git  
cd SignLanguaugeTranslator
Install Dependencies:
Ensure Python 3.7+ is installed, then run:

bash
Copy code
pip install -r requirements.txt  
Launch the Application:
Start the Streamlit app:

bash
Copy code
streamlit run app.py  
---

### **Live Demo**
Explore the project's capabilities with these video demonstrations:
![WIN_20220811_16_28_57_Pro](https://github.com/user-attachments/assets/f0d8784c-c772-45fa-932f-1bc256e721ae)

---
### **Technical Workflow**
Detection Framework:
Utilizes YOLOv5 for object detection, splitting images into grids and consolidating results using Non-Maximum Suppression.

Input Options:

Upload media (images/videos).
Use live webcam feeds.
Output:
Displays bounding boxes around detected gestures with labels and confidence scores.
---

### **Model Evaluation**
Performance metrics on the testing dataset:

Precision: 98.3%
Recall: 98.7%
F1 Score: 98.5%
mAP (Mean Average Precision): 99.3%
Overall Accuracy: 98.9%
📂 Dataset Details
The dataset consists of 3,399 images representing the 26 ASL alphabet gestures. It includes detailed annotations, optimized for training YOLOv5 models.

### **Exploratory Models**
CNN-Based Approach:
Tested convolutional neural networks for ASL detection with moderate success.

MediaPipe Framework:
Utilized MediaPipe Holistic for hand gesture and pose recognition.
---

### **Resources and Citations**
https://docs.ovh.com/asia/en/publiccloud/ai/training/web-service-yolov5/









