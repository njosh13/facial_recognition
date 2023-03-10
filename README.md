# Facial recognition

## Introduction:

This is a Python-based facial recognition project that uses dlib, OpenCV, and face_recognition libraries. The project aims to recognize and identify human faces from images or videos using machine learning and computer vision techniques.

## System Requirements:

1. Python 3.8 installed or higher
2. dlib, OpenCV, and face_recognition libraries (downloaded using pip)
3. Webcam , (USB-powered webcam if using WSL) -> you can check out how to use this with this docs: https://learn.microsoft.com/en-us/windows/wsl/connect-usb
4. Installed C++ packages from Visual Studio (if using Windows). This is to run dlib. If you are on linux follow the link:https://kumarvinay.com/installing-dlib-library-in-ubuntu/
5. Requirements.txt file that has all this dependencies

## Installation:

1. Clone the project from the GitHub repository.
2. Create a virtual environment using the venv command.
3. Install the required dependencies using pip and the requirements.txt file.

## Note for WSL Users:

Using an inbuilt camera on a laptop is not possible in WSL, but a USB-powered webcam can be used. Follow Microsoft's provided link for USB and WSL.

## Note for Windows Users:

Before anything else, download all C++ packages using Visual Studio.

## Usage:

1. Launch the application from the command line by running the main.py file.
2. The program will open your webcam and try to identify you by comparing your face with the photos of yourself that have been added in the code.
3. If your face is recognized, the program will output your name or ID.
4. If the program fails to recognize your face, you can add more photos of yourself to improve recognition accuracy.
5. You can also test the program's ability to recognize other faces by showing it photos of people like Elon Musk and Barack Obama. The program already has images of them, so it should be able to recognize them.

## Conclusion:

This project is a simple and effective facial recognition tool that can be used for various applications. If you encounter any issues or have suggestions for improvement, feel free to contact the project's author.
