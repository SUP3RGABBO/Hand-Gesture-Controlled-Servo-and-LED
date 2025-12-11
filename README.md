## Hand-Gesture-Controlled-Servo-and-LED
This project uses a webcam and the MediaPipe library to recognize hand gestures and control a servo motor and an LED via Arduino.
This project uses a webcam and the MediaPipe library to recognize hand gestures and control a servo motor and an LED via Arduino.

- The **servo** moves based on the distance between the thumb and index finger.
- The **LED** is on by default and turns off when the hand is closed (thumb close to index and pinky close to thumb).
- The project uses Python for image processing and PySerial for communication with Arduino.
## Requirements
- Python 3.x
- Python libraries: `opencv-python`, `mediapipe`, `pyserial`, `numpy`, `matplotlib`
- Arduino UNO or similar
- Servo motor and LED connected to Arduino

## Instructions
1. Upload the Arduino code to your Arduino board using Arduino IDE.
2. Run `main.py` with Python.
3. Move your hand in front of the webcam to control the servo and LED.
