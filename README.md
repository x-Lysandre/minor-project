# 🖌️ Air Canvas with Equation Solver ✍️ ➕➗  
This project is a virtual drawing tool that allows users to draw in the air using hand gestures via webcam. It also recognizes and solves mathematical equations drawn in the air using machine learning and OpenCV. The goal is to provide a fun and intuitive interface where users can draw or write without touching a screen — just with a wave of a hand!  

## 🚀 Features
✋ Air drawing using hand gestures  

🎨 Virtual color palette to switch brush colors  

🧼 Eraser tool for removing strokes  

💾 Save drawings as image files  

➕ Equation recognition and solving using OCR and machine learning  

👁️ Real-time hand tracking using MediaPipe  

## 🛠️ Technologies Used
Python

OpenCV

MediaPipe

NumPy

TensorFlow / Scikit-learn (for recognition model)

## 🧠 How It Works
### Hand Detection  

Uses MediaPipe to detect hand landmarks in real time from the webcam feed.  

Tracks fingertip (usually index finger) to draw lines on a virtual canvas.  

### Drawing Tools    

Toolbar on top for color selection and eraser.  

Pressing different areas of the screen activates tools via finger position.  

### Equation Mode

Switch to equation mode and write mathematical expressions in the air.

Captured image is processed and passed to an OCR/digit recognition model.

The equation is parsed and solved using Python.

## 📸 Demo
📽️ [Watch the demo]('demo video.mp4')


## 📁 Folder Structure
bash
Copy
Edit
📦 Air-Canvas-Equation-Solver
 ┣ 📜 equation_solver.py         # Expression recognition and evaluation  
 ┣ 📜 README.md  
## ▶️ How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/air-canvas-equation-solver.git
cd air-canvas-equation-solver
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the app:

bash
Copy
Edit
python air_canvas.py
🔮 Future Improvements
Add character-level OCR for better equation parsing

Voice feedback for evaluated equations

Multi-hand gesture support (e.g., one hand to draw, one to toggle tools)

## 🙌 Acknowledgments
MediaPipe

OpenCV

Inspired by virtual whiteboard and gesture recognition apps

## 📬 Contact
📧 negivj3000@gmail.com
🔗 LinkedIn
💻 GitHub

