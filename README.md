# Multi-Modal-Approach-for-Osteosarcoma-Stage-Detection
This project implements a deep learning-based web application to classify osteosarcoma X-ray images into five distinct stages: Doubtful, Healthy Knee, Minimal, Moderate, and Severe. The system leverages multiple CNN architectures including a custom CNN, ResNet152V2, and VGG16, and is integrated into a Flask web app for real-time predictions.

PROJECT OVERVIEW       
Osteosarcoma is an aggressive form of bone cancer. Accurate and early detection is critical for improving patient outcomes. This project automates X-ray classification into meaningful clinical stages using advanced medical imaging classification techniques, allowing healthcare professionals to make informed decisions.    

HOW TO RUN THE PROJECT         
1. Clone the Repository:        
git clone https://github.com/KaustubhHari/Multi-Modal-Approach-for-Osteosarcoma-Stage-Detection.git          
cd osteosarcoma-stage-classification      

2. Set Up Environment:          
pip install -r requirements.txt     
(Make sure you have TensorFlow, Keras, OpenCV, Flask, NumPy, and Matplotlib installed)

3. Run the Flask App:         
python app.py             
Go to http://127.0.0.1:5000 in your browser and test the application.

📸 SAMPLE PREDICTION
![Screenshot_20250509_101335](https://github.com/user-attachments/assets/aa06b4be-c9ca-4b29-9f54-b9598f4827dd)
