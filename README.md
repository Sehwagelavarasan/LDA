😊 Facial Emotion Filter WebApp 
A web application that detects facial emotions from images or webcam input and applies fun filters based on the detected emotions. This project showcases the combination of computer vision and web development to create an engaging user experience.

🚀 Features 
Real-time facial emotion detection using webcam

Upload image and detect emotions

Emotion-based filters applied dynamically (e.g., smile = sunglasses 😎)

Clean and responsive UI

Built with modern web technologies and machine learning

🧠 Tech Stack

Backend: Flask / Node.js 

Machine Learning: OpenCV, sklearn,flash,matplotlib

📸 How It Works
The user uploads a photo or uses their webcam.

The system detects the face and analyzes emotional expressions.

Based on the emotion (happy, sad, angry, etc.), a filter is applied (e.g., funny glasses, tears, devil horns).

The filtered image is displayed or downloadable.

🛠️ Installation
bash
Copy
Edit
git clone https://github.com/Sehwagelavarasan/LDA?tab=readme-ov-file
cd facial-emotion-filter-webapp
Backend (if using Flask):
bash
Copy
Edit

pip install -r requirements.txt
python app.py

Frontend:
Just open index.html in your browser if it's a frontend-only app, or run it via your backend server.

📁 Project Structure
php
Copy
Edit
facial-emotion-filter-webapp/
│
├── static/              # CSS, JS, images, filter overlays
├── templates/           # HTML templates (if Flask)
├── model/               # Pre-trained emotion detection models
├── app.py / server.js   # Backend logic
├── README.md
└── requirements.txt / package.json
🧪 Demo
[Insert link here if hosted]
You can also include a GIF or image of your app in action!

🤖 Emotion Classes
Happy
Sad
Angry
Normal
Fear


📌 To Do
 Add multiple faces support

 Add downloadable image with filter

 Optimize for mobile



















