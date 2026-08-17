# Real time Indian Sign Language Interpretation System Using Python and Open-CV
The Indian Sign Language System is a real-time communication solution that uses computer vision and deep learning to recognize ISL gestures through a live camera. It converts recognized signs into text and speech, helping bridge communication gaps between sign language users and non-signers.The system promotes accessibility,communication.

# 🚀 Features

Real-time Recognition: Live two-handed gesture recognition.

Professional Web Interface: Modern, responsive design

Easy Controls: Start/Stop/Exit prediction with one click

Learning Resources: Integrated ISL tutorial links

Mobile Responsive: Works on all devices
# 📋 Requirements
Python 3.7+
OpenCV
MediaPipe
TensorFlow
Flask
Flask-CORS
#🛠️ Installation
Install Python dependencies:

pip install -r requirements.txt
Run the application:

python app.py
Open your browser:

Go to http://localhost:5000
Allow camera access when prompted
#🎯 Usage
Start Prediction: Click "Start Prediction" to begin recognition
Stop Prediction: Click "Stop Prediction" to pause
Exit: Click "Exit" to close the application
Learn ISL: Use the learning resource cards for tutorials
#📁 Project Structure
ISL_Interpreter_2Hands/
├── app.py                    # Main Flask application
├── simple_frontend.html      # Professional web interface
├── requirements.txt          # Python dependencies
├── model/                    # Trained ML models
│   ├── isl_model_two.keras
│   └── label_encoder_two.pkl
├── data/                     # Training data
│   └── isl_landmarks_two.csv
├── static/                   # CSS styles
├── templates/                # Flask templates
└── utils_preproc_two.py      # Data preprocessing utilities
🔧 Development
Training: python train_model_two_hands.py
Data Collection: python collect_data_two_hands.py
Real-time Testing: python realtime_isl_two_hands.py
#🎨 Interface
The web interface features:

Dark Professional Theme: Modern, business-ready design
Real-time Video Feed: Live camera input with gesture overlay
Control Panel: Intuitive start/stop controls
Learning Section: Direct links to ISL tutorials
Responsive Design: Works on desktop and mobile
#📱 Browser Support
Chrome (recommended)
Firefox
Safari
Edge
#🔒 Privacy
All processing happens locally
No data is sent to external servers
Camera access is only used for gesture recognition
