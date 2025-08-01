
# Face based attendance system using python and openCV

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 
[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/) 

### What steps you have to follow??
- Download or clone my Repository to your device
- type `pip install -r requirements.txt` in command prompt(this will install required package for project)
- Create a `TrainingImage` folder in a project folder.
- open `attendance.py` and `automaticAttendance.py`, change all the path accoriding to your system
- Run `attandance.py` file

### Project flow & explaination
- After you run the project you have to register your face so that system can identify you, so click on register new student
- After you click a small window will pop up in that you have to enter you ID and name and then click on `Take Image` button
- After clicking `Take Image` button A camera window will pop up and it will detect your Face and take upto 50 Images(you can change the number of Image it can take) and stored in the folder named `TrainingImage`. more you give the image to system, the better it will perform while recognising the face.
- Then you have to click on `Train Image` button, It will train the model and convert all the Image into numeric format so that computer can understand. we are training the image so that next time when we will show the same face to the computer it will easily identify the face.
- It will take some time(depends on you system).
- After training model click on `Automatic Attendance` ,you have to enter the subject name and then it can fill attendace by your face using our trained model.
- it will create `.csv` file for every subject you enter and seperate every `.csv` file accoriding the subject
- You can view the attendance after clicking `View Attendance` button. It will show record in tabular format.
<div id="top"></div>

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)

<h3 align="center">Face Based Attendance System</h3>

<p align="center">
  A real-time facial recognition-based attendance system using Python, OpenCV, and machine learning.
  <br />
  <a href="https://github.com/Kusuma71/Face-Attendance-System"><strong>View Repository »</strong></a>
</p>

---

## 🧠 Project Overview

This project was developed by <b>S. Kusuma</b> as part of a practical learning experience to integrate computer vision with real-time face recognition for managing student attendance. The system captures face data, trains a recognition model, and records attendance in a CSV file.

---

## 🎯 Key Features

- 📷 Face registration and training using webcam
- 🧠 Face recognition for marking attendance
- 📂 Attendance records stored subject-wise in CSV format
- 📊 View attendance in tabular format via UI
- 🧍 Multiple user support
- 🔒 Real-time verification and secure input
- 🖼️ GUI built with Tkinter
- ✅ Simple, clean UI and file structure

---

## ⚙️ Technologies Used

| Category        | Tools & Libraries                                   |
|-----------------|-----------------------------------------------------|
| 👨‍💻 Programming  | Python 3.6                                          |
| 🧠 ML & Vision   | OpenCV, NumPy, Scikit-learn                         |
| 🖼️ GUI           | Tkinter                                            |
| 📋 Data Handling | Pandas                                             |
| 💾 File Storage  | CSV                                                |
| 🧪 Testing Tools | Command Line, IDE                                  |

---

## 🪜 Steps to Run the Project

1. Download or clone this repository
2. Install required packages:
   ```bash
   pip install -r requirements.txt

### Screenshots

### Simple UI
<img src='https://github.com/Patelrahul4884/Attendance-Management-system-using-face-recognition/blob/master/Project%20Snap/1.PNG'>
for more Screenshots go to  -Project snap file

## Just follow me and Star⭐ my repository
