# 🎥 Face Recognition Attendance System

An innovative Face Recognition-based Attendance System that uses deep learning to capture and recognize student faces, update attendance records in real-time using Firebase, and provide a user-friendly GUI for manual database management.


## ✨ Features

- **🎬 Real-Time Face Recognition**: Detects and recognizes student faces in real-time using a webcam and deep learning techniques.
- **📊 Firebase Integration**: Seamlessly stores and manages student data and attendance records using Firebase Realtime Database.
- **📈 Automatic Attendance Marking**: Automatically updates attendance status in Firebase for recognized students.
- **🖥️ Manual Database Management GUI**: Built with `Tkinter`, this GUI allows for easy addition, removal, and modification of student records.
- **📤 Export to Excel**: Easily export student data to an Excel file for reporting and analysis.

## 🔍 Code Overview

**📝 Main Components**
- **`Main.py`**: The primary script for face recognition, attendance marking, and database interaction.
- **`studentmanagement.py`**: A GUI application for managing the student database manually.
- **`EncodeGenerator.py`**: A script to generate and store facial encodings.

## 🔧 Key Functions in `Main.py`
- **Face Detection and Recognition**: Utilizes the `face_recognition` library to identify students.
- **Attendance Marking**: Updates Firebase in real-time based on recognized faces.
- **Firebase Operations**: Manages interactions with the Firebase Realtime Database.

**🖥️ GUI Features in `studentmanagement.py`**
- **CRUD Operations**: Add, remove, update student records with ease.
- **Export Functionality**: Export data to Excel for further analysis.

