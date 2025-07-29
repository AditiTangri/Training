# ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING
## PROJECT : Face Recognition-Based Attendance System  
**DAY : 23**

**Date:** 23 July 2025  


---

## Results 

### Face Encoding
- Loaded and encoded known faces from the `Data/` folder.
- Each face was converted into a unique numerical format for recognition.

### Real-Time Detection
- Opened webcam and detected faces in real-time.
- Compared detected faces with known ones using facial encodings.
- Green box: Recognized person  
- Red box: Unknown face

### Attendance Logging
- Recognized faces were marked in `attendance.csv` with date and time.
- Each person was marked only once per session to avoid duplicates.

### System Feedback
- Printed messages like:
  - `"Encoding Complete"`
  - `"[Name] already marked present"`
  - `"Unknown face detected"`
  - `"Exit command received"` when quitting

### Testing
- Worked well in good lighting and with clear faces.
- Accuracy dropped with poor lighting or side angles.

---

## Conclusion
- Easy to use, fast, and accurate in real-time.
- Can be improved further with better lighting and more training data.

**By:** Aditi Tangri 

**URN:** 2302460 

**CRN:** 2315004  
