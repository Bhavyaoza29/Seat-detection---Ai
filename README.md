🪑 Vacant Seat Detection: Making Campus Life Easier
👥 Team Members
Bhavya Oza, Yashvi T, Freya Trivedi, Jiya Patel

University: UIT, Karnavati University

🚀 Project Overview
Finding a vacant seat during peak hours in a university canteen or library is harder than it should be.
Our project tackles this common problem by detecting vacant seats in real-time, using computer vision and deep learning.

Built with YOLOv5, OpenCV, and Tkinter, this system helps students quickly locate available seats, saving valuable time and reducing daily frustration.

🎯 Why We Built This
Save time: Help students avoid wandering around searching for free seats.

Reduce stress: Ease peak-time crowd management in shared spaces.

Leverage AI: Build smarter campus facilities through real-time detection.

🛠️ Tech Stack

Purpose	Tools
Object Detection	YOLOv5
Image Processing	OpenCV
GUI (Desktop App)	Tkinter
Backend (Planned)	Flask
Frontend (Planned)	HTML, CSS, JavaScript
Data Annotation	Roboflow
Model Training Environment	Anaconda + YOLOv5
🧠 How It Works
Data Collection:

Captured canteen images manually; used Roboflow datasets for libraries.

Annotation and Model Training:

Labeled data and trained a custom YOLOv5 model (best.pt).

Real-Time Detection:

Webcam captures live feed.

YOLOv5 detects seats and occupancy.

Tkinter displays real-time annotated frames.

(Next Step):

Extend to a web application using Flask and real-time dashboards.

🖥️ Setting It Up
To run the project on your local machine:

1. Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2. Install the required libraries
bash
Copy
Edit
pip install torch torchvision opencv-python pillow
3. Run the app
bash
Copy
Edit
python app.py
(Make sure you update any file paths as per your system.)

📸 What You’ll See
Once you run the app:

Your webcam opens.

The system detects vacant and occupied seats in real-time.

A simple Tkinter window displays annotated video feed instantly.

⚡ Features
Live seat detection using a laptop webcam.

Lightweight and fast, built with minimal dependencies.

Easy to extend into web and mobile applications.

📈 Results & Learnings
Accuracy: The model performs reliably under normal lighting and camera conditions.

Challenges faced:

Variations in lighting and angles affecting detection.

Dense seating making IoU-based vacancy detection tricky.

Despite these hurdles, the system consistently identifies seat occupancy in real-world scenarios.

🔮 What's Next
Build a mobile app version.

Expand coverage to auditoriums, study halls, and libraries.

Add notifications for when a seat becomes available.
