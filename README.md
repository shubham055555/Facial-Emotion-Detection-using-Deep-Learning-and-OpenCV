😃 Facial Emotion Detection using Deep Learning and OpenCV
This project is a real-time facial emotion recognition system that uses a trained deep learning model (CNN) to detect and classify human emotions from webcam video feed. It identifies emotions such as Happy, Sad, Angry, Fear, Surprise, Disgust, and Neutral using OpenCV and Keras.

🔍 Features
Real-time emotion detection from webcam

Deep learning-based facial expression recognition

Uses Haar Cascade for face detection

Pre-trained Keras model (.json + .h5)

Labels emotions on faces in live video stream

face-emotion-detection/
│
├── emotiondetector.json         # Model architecture
├── emotiondetector.h5           # Model weights
├── emotion_detection.py         # Main Python script
└── README.md                    # Project documentation

pip install opencv-python keras numpy
🧠 Emotions Recognized
😠 Angry

🤢 Disgust

😨 Fear

😀 Happy

😐 Neutral

😢 Sad

😲 Surprise

📌 Notes
The face detection is handled by OpenCV's Haar cascade classifier.

The model is trained on grayscale 48x48 facial expression images.

Model files are not included due to size — you can train your own or contact me for the files.

🙋‍♂️ Author
Shubham
B.Tech CSE (AI & ML), KR Mangalam University
📜 License
This project is open-source and available under the MIT License.
