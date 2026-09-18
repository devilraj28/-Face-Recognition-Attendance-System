# Class Vision - Smart Face Recognition Attendance System

## 1. Project Overview

Class Vision is a Python-based face recognition attendance management system designed to automate the process of recording student attendance.

The system uses OpenCV for face detection and recognition. Students can register their details and face images, train the face recognition model, and later use face recognition to automatically record attendance.

The attendance records are stored as CSV files and can be viewed in a tabular format.

---

## 2. Problem Statement

Traditional attendance systems require teachers to manually record student attendance, which can be time-consuming and may result in errors.

The purpose of Class Vision is to provide a simple computer vision based solution that can identify registered students through their faces and record their attendance automatically.

---

## 3. Objectives

The main objectives of this project are:

- To automate the student attendance process.
- To detect and recognize registered student faces.
- To maintain student information digitally.
- To reduce manual attendance work.
- To store attendance records in CSV format.
- To provide a simple graphical user interface.
- To apply computer vision concepts in a real-world application.

---

## 4. Scope of the Project

The project can be used in educational environments such as:

- Classrooms
- College laboratories
- Training institutes
- Small educational organizations

The system focuses on face-based identification and attendance recording using a local computer and webcam.

---

## 5. Features

### 5.1 Student Registration

Students can register their enrollment ID and name in the system.

### 5.2 Face Image Capture

The system uses a webcam to detect the student's face and capture multiple face images for training.

### 5.3 Face Recognition Model Training

Captured face images are processed and used to train the face recognition model.

### 5.4 Automatic Attendance

The trained model is used to recognize registered students through the webcam and record their attendance.

### 5.5 Subject-wise Attendance

Users can enter a subject name before taking attendance. Attendance records are organized according to the subject.

### 5.6 Attendance Records

Attendance is stored in CSV files containing student enrollment information and attendance data.

### 5.7 Attendance Viewing

The recorded attendance can be opened and displayed in a tabular format.

### 5.8 Text-to-Speech Feedback

The system provides voice feedback for important actions using the text-to-speech functionality.

---

## 6. Functional Requirements

The system provides the following major functional modules:

### Module 1: Student Registration

**Input:**
- Student Enrollment ID
- Student Name
- Face images captured using webcam

**Output:**
- Student details stored in the system
- Face images stored for training

### Module 2: Face Recognition and Training

**Input:**
- Captured student face images

**Processing:**
- Face detection
- Image processing
- Face recognition model training

**Output:**
- Trained face recognition model

### Module 3: Automatic Attendance

**Input:**
- Subject name
- Student face through webcam

**Processing:**
- Face detection
- Face recognition
- Student identification

**Output:**
- Attendance record stored in CSV format

### Module 4: Attendance Management

**Input:**
- Stored attendance records

**Output:**
- Attendance displayed in tabular format
- Subject-wise attendance files

---

## 7. Non-Functional Requirements

### 7.1 Usability

The system provides a graphical user interface so that users can perform registration, training, attendance, and attendance viewing without using complex commands.

### 7.2 Performance

The system performs face detection and recognition using OpenCV and processes the webcam input in real time.

### 7.3 Reliability

Student information and attendance records are stored in files so that recorded data can be accessed after the attendance process.

### 7.4 Maintainability

The project is divided into multiple Python files/modules for different operations such as registration, image capture, model training, attendance processing, and attendance viewing.

### 7.5 Error Handling

The system provides messages and voice feedback for situations such as an empty subject name, missing trained model, or unsuccessful face detection.

---

## 8. System Workflow

The general workflow of Class Vision is:

```text
Start Application
       |
       v
Register Student
       |
       v
Capture Face Images
       |
       v
Train Face Recognition Model
       |
       v
Enter Subject Name
       |
       v
Start Automatic Attendance
       |
       v
Detect Face
       |
       v
Recognize Student
       |
       v
Record Attendance
       |
       v
Save Attendance as CSV
       |
       v
View Attendance