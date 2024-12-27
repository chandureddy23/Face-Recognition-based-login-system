# **Face Detection-Based Login and Registration System**

## **Overview**
This project is a GUI-based facial recognition login and registration system implemented in Python. It utilizes the **Tkinter** library for the user interface, **OpenCV** for webcam capture, and **Mediapipe** for real-time face detection. The application allows users to:
- Log in using their facial data.
- Register as new users by capturing their face via webcam.

---

## **Features**
- **Real-Time Face Detection**: Detects faces in real-time using Mediapipe's face detection module.
- **Login Functionality**: Matches a user's face with saved records to allow access.
- **User Registration**: Captures a user's image and stores it in the database for future logins.
- **Interactive GUI**: Clean and intuitive user interface for a seamless experience.

---

## **Technologies Used**
- **Python**: Core programming language.
- **Tkinter**: For GUI creation.
- **OpenCV**: For webcam video capture and image processing.
- **Mediapipe**: For facial detection and processing.
- **Pillow**: For handling images in the application.

---

## **Getting Started**

### Prerequisites
- Python 3.7 or later.
- Required Python libraries:
  ```bash
  pip install opencv-python mediapipe pillow
  ```

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/facial-login-system.git
   cd facial-login-system
   ```

2. Install dependencies:
   ```bash
   pip install opencv-python mediapipe pillow
   ```

3. Run the application:
   ```bash
   python app.py
   ```

---

## **Directory Structure**
```plaintext
facial-login-system/
├── images/
│   └── known_imgs/       # Stores registered user images
├── app.py                # Main application script
└── README.md             # Project documentation
```

---

## **Usage**

### **1. Login**
- Click the "Login" button to log in using your face.
- If your face is recognized, you'll be granted access.
- If unrecognized, the system will display a warning.

### **2. Register New User**
- Click the "Register new user" button to open the registration window.
- Enter your name in the text box and click "Accept" to save your face for future logins.

---

## **Screenshots**
![image](https://github.com/user-attachments/assets/988c3515-691f-48bb-a2d7-9e19c3ceef6f)

### **Main Window**
![image](https://github.com/user-attachments/assets/057585e5-58c5-4eaa-83f4-c5896501c5cc)
![image](https://github.com/user-attachments/assets/254bb278-855f-45ac-90e3-1028935b5627)

### **User Registration**
![image](https://github.com/user-attachments/assets/e3819da4-a974-4d01-852e-a44660ad7158)

---

## **Known Issues**
- No persistence for face recognition beyond captured images.
- Facial recognition logic for user login is placeholder and needs integration with advanced models like `face_recognition`.

---

## **Future Enhancements**
- Add support for robust facial recognition using deep learning models.
- Enhance security measures to prevent spoofing.
- Store user details in a database instead of local directories.

---

## **Contributing**
Feel free to fork the repository and make changes. Create a pull request to submit your improvements.

