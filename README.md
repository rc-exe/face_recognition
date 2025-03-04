 Face Expression Recognition

 Overview
This project captures facial expressions and detects emotions in real time using OpenCV and DeepFace.

 Features
- Real-time face detection using OpenCV
- Emotion recognition using DeepFace
- Webcam integration
- Displays detected emotion on the screen

 Requirements
Ensure you have Python installed, then install the required dependencies:
bash
pip install opencv-python numpy tensorflow keras deepface tf-keras


 Virtual Environment Setup (Recommended)
To create and activate a virtual environment:
bash
python -m venv venv

- Windows:
  bash
  .\venv\Scripts\activate
  
- Mac/Linux:
  bash
  source venv/bin/activate
  
Then, install the dependencies inside the virtual environment:
bash
pip install opencv-python numpy tensorflow keras deepface tf-keras


 How to Run
1. Clone the repository or download the files.
2. Navigate to the project directory.
3. Activate the virtual environment (if created).
4. Run the script:
   bash
   python emotion_recognition.py
   
5. Press 'q' to exit the program.

 Troubleshooting
- If you encounter ModuleNotFoundError: No module named 'tf_keras', install tf-keras:
  bash
  pip install tf-keras
  
- If DeepFace raises TensorFlow compatibility errors, downgrade TensorFlow:
  bash
  pip install tensorflow==2.10.0
  

 Future Improvements
- Add Flask-based web UI
- Train a custom deep learning model for improved accuracy
- Save detected emotions for analysis

 License
This project is for educational purposes only.

---
© 2025 Ritesh Chakramani. All rights reserved.

