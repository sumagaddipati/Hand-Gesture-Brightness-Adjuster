**Gesture-Based Brightness Control Using OpenCV & MediaPipe**

Adjust your screen brightness with just hand gestures! This project utilizes MediaPipe Hands and OpenCV to detect finger distance and map it to brightness levels.

**Features**

✅ Real-time hand tracking using MediaPipe

✅ Adjusts screen brightness using screen-brightness-control

✅ Works smoothly with webcams

✅ Simple and intuitive gesture-based control

Tech Stack

Python 🐍

OpenCV 🎥

MediaPipe 🖐

screen-brightness-control ☀️

**Demo**

![Screenshot 2025-02-23 110400](https://github.com/user-attachments/assets/71f292a2-1cf1-4e51-af98-689a4f2f37c0)


**Usage**

Bring your thumb and index finger close to decrease brightness 🌑

Move them apart to increase brightness ☀️

Press 'q' to exit

**Code Overview**

The script captures video from the webcam and uses MediaPipe Hands to detect hand landmarks. It then calculates the distance between the thumb and index finger and maps it to the screen brightness using screen-brightness-control.

**Key Functions:**

Hand Tracking: Uses MediaPipe to detect hand landmarks in real-time.

Distance Calculation: Computes the Euclidean distance between the thumb and index finger.

Brightness Mapping: Maps the distance to the screen brightness range and adjusts accordingly.

Real-Time Adjustment: Continuously updates the brightness based on hand gestures.

**Contribute**

Feel free to fork and improve the project! 🎉



