# Smart Attendance System

## Overview

The **Smart Attendance System** is an AI-powered application that automates attendance tracking using **face recognition technology**. It is designed to eliminate manual attendance errors and prevent proxy attendance by accurately identifying individuals in real time.

The system uses **computer vision and machine learning techniques** to detect and recognize faces through a webcam, automatically recording attendance with timestamps. It provides a reliable, secure, and efficient solution suitable for educational institutions and organizations.

This project has been refined and structured by **Malith Hanchapola** as part of my work in Python development, computer vision, and intelligent systems.

## Features

* **Face Registration:** Register students with facial data
* **Real-Time Recognition:** Detect and recognize faces using a webcam
* **Automatic Attendance:** Mark attendance with timestamps instantly
* **Proxy Prevention:** Prevent unauthorized attendance marking
* **Unknown Face Detection:** Identify and flag unregistered users
* **Admin Dashboard:** Manage attendance records efficiently
* **Export Options:** Download attendance reports (CSV / Excel)
* **Manual Mode:** Backup option for manual attendance entry

## Technologies Used

* **Backend:** Python (Flask), Flask-SQLAlchemy
* **Computer Vision:** OpenCV, face_recognition (dlib)
* **Frontend:** HTML5, CSS3, JavaScript
* **Database:** SQLite
* **Libraries:** NumPy, Pandas, Pillow

## System Requirements

* Python 3.7 or higher
* Webcam
* Minimum 4GB RAM
* Compatible OS: Windows / macOS / Linux

## Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/smart-attendance-system.git
cd smart-attendance-system
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
python app.py
```

### 4. Access the system

Open your browser and navigate to:

```
http://localhost:5000
```

## Important Setup (Dlib)

This project requires **dlib** for face recognition.

If installation fails:

* Install **CMake**
* Install **Visual Studio C++ Build Tools** (Windows)
* Restart your terminal

## Usage

### Automatic Mode

1. Register student images
2. Start the camera
3. Enable face recognition
4. System detects faces automatically
5. Attendance is recorded instantly

### Manual Mode

* Enter student ID manually
* Mark attendance as a backup option

## Security & Privacy

* Face data is processed locally
* No cloud dependency
* No raw biometric data sharing
* Secure storage of face encodings

⚠️ **Note:** Always obtain user consent before using facial recognition systems.

## Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch:

   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:

   ```bash
   git commit -m "Add new feature"
   ```
4. Push to GitHub:

   ```bash
   git push origin feature-branch
   ```
5. Open a pull request

## License

This project is licensed under the **MIT License**.
See the LICENSE file for details.

## Contact

For suggestions or collaboration:

* **Email:** [malithhanchapola.dev@gmail.com](mailto:malithhanchapola.dev@gmail.com)
* **GitHub:** [https://github.com/yourusername](https://github.com/yourusername)


