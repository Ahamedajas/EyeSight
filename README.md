# EyeSight: Non-Invasive Diabetic Retinopathy Detection Using Deep Learning

**EyeSight** is a web-based solution for non-invasive, cost-effective early detection of Diabetic Retinopathy (DR) using pupillometry and ensemble deep learning models. It is designed to aid clinicians in remote and underserved areas by providing real-time predictions and severity classification without the need for traditional expensive imaging techniques.

## 🌟 Short Description

Diabetic Retinopathy is a major cause of vision loss in diabetic patients. Traditional screening methods are often invasive, expensive, and inaccessible in rural areas. EyeSight addresses this challenge using pupillometry data and deep learning models to predict DR severity levels in real time.

---

## 🚀 Features

- 🎯 Upload pupillometry recordings for analysis  
- 🧠 Deep learning-based DR severity detection  
- 📊 Real-time predictions with confidence scores  
- 🖥️ User-friendly web interface  
- 🩺 Clinician-focused design for early intervention  
- 🧾 Classifies into: **Healthy**, **Mild**, **Moderate**, **Severe**, **Proliferative**

---

## 🧑‍💻 Tech Stack

- **Frontend**: React (Vite)
- **Backend**: Python
- **Models**: ResNet, DenseNet, EfficientNet
- **Deployment**: Frontend on Vercel | Backend runs locally

---

## ⚙️ Setup Instructions

### Backend Setup

1. Clone the repository and navigate to the backend folder.
2. Create a virtual environment using Anaconda:
    ```bash
    conda create -n eyesight-env python=3.10
    conda activate eyesight-env
3. Install the required dependencies:
    pip install -r requirements.txt
4. Run the backend server:
    python app.py
5. Ensure the backend is running on a local port (e.g., http://localhost:5000)

### Frontend Setup

1. Navigate to the frontend folder:
    cd eyesight-frontend
2. Install dependencies and run locally:
    npm install
    npm run dev
Note: The frontend is already deployed, so local setup is optional.

## 🌐 Deployed Application

🔗 Live Demo: https://eyesight-dr.vercel.app/


