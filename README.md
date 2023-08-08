# Fcae_Recognized_Attendance_System

# Face Recognition Attendance System

This project demonstrates a face recognition-based attendance system using Python, the `face_recognition` library, and OpenCV. The system captures real-time video from a webcam, detects faces in the video stream, and matches them with pre-registered faces to mark attendance. The attendance records are stored in a CSV file for easy tracking and management.

## Features

- Real-time face detection and recognition from webcam feed.
- Comparison of detected faces with pre-registered face encodings to determine attendance.
- Display of recognized faces in the video feed along with attendance status.
- Automatic recording of attendance records in a CSV file, including name, date, and time.
- User-friendly interface that allows easy setup and usage.
- Ability to extend the system to accommodate multiple users.

## Getting Started

To get started with the project, follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python packages: `face_recognition`, `cv2` (OpenCV).
3. Place the images of the individuals whose attendance you want to track in the `facesid` directory.
4. Run the `attendance_system.py` script using Python.

Make sure you have a webcam connected to your machine for the system to work.

## Usage

1. Run the script and allow it access to your webcam.
2. The system will display the video feed with recognized faces marked as "present."
3. Press the "q" key to exit the system when you're done.

The attendance records will be automatically saved in CSV files named according to the date.

## Future Improvements

This project serves as a foundation for building more advanced attendance systems and can be extended in various ways:

- Implementing user authentication for secure attendance tracking.
- Adding a web-based front end for remote attendance tracking and management.
- Integrating with other data storage and management systems.
- Enhancing the face recognition model's accuracy and efficiency.

Feel free to contribute to this project by submitting pull requests or suggesting new features!

## Acknowledgments

This project was inspired by the need for efficient attendance tracking systems and utilizes the power of face recognition technology to achieve this goal.

---

Feel free to modify and customize the above description to match your project's specifics and any additional features you might add.
