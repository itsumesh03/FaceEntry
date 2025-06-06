🧠 FaceEntry: Facial Recognition Attendance System
FaceEntry is a Python-based machine learning application for managing attendance using facial recognition technology. Built with OpenCV, Tkinter, and other libraries, this desktop app captures, trains, and recognizes faces to automatically record attendance.
# Screenshot
![faceimg_home](https://github.com/user-attachments/assets/2a9d56e5-e328-4816-9bbc-fea9e17785ca)
![faceimg2](https://github.com/user-attachments/assets/3209d057-d86f-421a-894c-133f1ee772c6)
![faceimg](https://github.com/user-attachments/assets/e0c4fa48-38e9-4401-a9c7-20124aea3b68)


📌 Features
🔐 Password-protected access to training module

🧑‍🎓 Register and capture facial data of new users

📷 Face detection using Haar Cascades

🧠 Face recognition using LBPH (Local Binary Pattern Histograms)

🗂️ Store user details and attendance in CSV format

🖼️ GUI built using Tkinter

🛠️ Secure password change and file handling

📊 Display of attendance in a table format with time/date

🏗️ Technologies Used
Python

OpenCV – for face detection and recognition

Tkinter – for GUI

NumPy, Pandas – for data handling

Pillow – for image processing

CSV, OS, Datetime – for file and date operations

🧪 Modules and Workflow
1. Registration & Image Capture
Users enter their ID and name.

The app captures 100 samples of the user's face using the webcam.

Images are saved in TrainingImage/.

2. Training
LBPH face recognizer is trained on saved facial images.

Trained model is stored in TrainingImageLabel/Trainner.yml.

3. Recognition & Attendance
Webcam scans for faces in real-time.

Recognized faces are matched with the trained data.

Attendance is saved in Attendance/ with a timestamp.

4. Password Security
Only users with a registered password can initiate training.

Password can be changed securely within the app.

📂 Directory Structure
bash
Copy
Edit
FaceEntry/
│
├── TrainingImage/                # Captured face images
├── TrainingImageLabel/          # Trained model and password file
├── Attendance/                  # CSV files with attendance logs
├── StudentDetails/              # Student registration details
├── haarcascade_frontalface_default.xml
├── main.py                      # Main application file
└── README.md


📧 Contact
If you encounter any issues or have suggestions:

Umesh Saini
📩 Email: Umeshsaini060@gmail.com
 
 
