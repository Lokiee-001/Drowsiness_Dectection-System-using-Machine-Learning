# 🛑 Real-Time Drowsiness Detection System

A Python and OpenCV-based project for real-time driver drowsiness and yawn detection using eye aspect ratio and facial landmarks. The system uses computer vision techniques to raise an alarm when drowsiness or yawning is detected — helping prevent road accidents.

---

## 🧠 Features

- ✅ Real-time face and eye detection
- ✅ Drowsiness detection using Eye Aspect Ratio (EAR)
- ✅ Yawn detection using lip distance
- ✅ Alarm triggered on fatigue or yawns
- ✅ Lightweight, fast, and camera-based (non-intrusive)
- ✅ Easy to run on any laptop with a webcam

---

## 👨‍💻 Developed By

**Lokeshwar L**  
> Final Year BCA Student  
> [Feel free to add your LinkedIn/GitHub profile here]

---

## 🧰 Tech Stack

| Tool        | Usage                                      |
|-------------|---------------------------------------------|
| Python 3.x  | Main programming language                   |
| OpenCV      | Image processing and face detection         |
| Dlib        | Facial landmark detection (68-point model)  |
| Imutils     | Simplified OpenCV operations                |
| Pygame      | Playing alarm sound                         |
| Scipy/NumPy | EAR and lip distance calculations           |

🗂️ Project Files

📁 Real-Time-Drowsiness-Detection-System/
├── drowsiness_yawn.py                  # Main script
├── check.py                            # Dlib version checker
├── Alert.wav                           # Alarm sound file
├── haarcascade_frontalface_default.xml # Haar cascade for face detection
├── shape_predictor_68_face_landmarks.dat # Dlib facial landmark model
├── Real_Time_Drowsiness_Detection_System.pdf # Project report
1. Install Python Packages
bash
Copy
Edit
pip install opencv-python dlib imutils numpy scipy pygame
2. Clone this Repository
bash
Copy
Edit
git clone https://github.com/your-username/Real-Time-Drowsiness-Detection-System.git
cd Real-Time-Drowsiness-Detection-System


3. Run the Detection Script
bash
Copy
Edit
python drowsiness_yawn.py --webcam 0 --alarm Alert.wav
You can replace the alarm file path if needed.

⚙️ Configuration Parameters
Argument	Description	Default
--webcam	Webcam index to use	0
--alarm	Path to .wav file for alarm	Alert.wav
