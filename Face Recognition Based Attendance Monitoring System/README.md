# Face Recognition Based Attendance System

This Python project implements an attendance system that uses face recognition to take attendance. The system is integrated with a user-friendly graphical user interface (GUI) to make it accessible for everyone. The GUI for this project is developed using Tkinter.

## Technologies Used
1. **Tkinter**: For the entire GUI.
2. **OpenCV**: For capturing images and face recognition using `cv2.face.LBPHFaceRecognizer_create()`.
3. **CSV, Numpy, Pandas, datetime**: For various data handling and processing tasks.

## Features
1. **User-Friendly Interface**: The system is easy to use with an interactive GUI.
2. **Password Protection**: Registration of new individuals is secured with a password.
3. **Automated CSV Management**: 
   - Creates or updates a CSV file with student details upon registration.
   - Generates a new CSV file each day for recording attendance, logging the date and time.
4. **Live Attendance Updates**: Displays real-time attendance updates on the main screen in a tabular format, showing ID, name, date, and time.

This face recognition-based attendance system simplifies the process of taking attendance, ensuring accuracy and efficiency. The integration of a GUI makes it accessible and easy to operate, while the use of OpenCV ensures robust face recognition capabilities.