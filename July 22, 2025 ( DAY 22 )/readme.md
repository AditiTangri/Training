# ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING
## PROJECT : Face Recognition-Based Attendance System   
**DAY - 22**

**Date:** 22 July 2025  

---

## Step-by-Step Workflow

### Problem Understanding & Planning
- Identified issues with manual and biometric attendance (e.g., proxies).
- Defined project goals, tools, and requirements.

### Dataset Preparation
- Collected face images and saved them in the `dataset/` folder.
- Named each image after the person (e.g., `john.jpg`) for easy identification.

### Face Encoding
- Converted face images into numerical encodings using Python.
- Stored encodings and names for recognition during runtime.

### Real-Time Face Detection & Recognition
- Used webcam to capture live video.
- Detected and encoded faces in real-time.
- Compared new encodings with known ones using Euclidean distance.

### Marking Attendance
- Saved recognized names and timestamps in `attendance.csv`.
- Marked each person only once per session to avoid duplicates.

### User Interface & Feedback
- Green box: recognized face with name  
- Red box: unknown face  
- On-screen messages showed system status.
- Pressing `'q'` stopped the system.

### Testing & Validation
- Tested under different lighting and angles.
- Checked for real-time performance and accurate attendance.
- Verified system behavior with known and unknown faces.



**By:** Aditi Tangri 

**URN:** 2302460 

**CRN:** 2315004  
