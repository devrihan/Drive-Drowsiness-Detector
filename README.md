# Driver-Drowsiness-Detector

---

**Description:**

The Driver Drowsiness Detector is a Python application designed to detect and alert the driver if they are exhibiting signs of drowsiness while driving. It utilizes computer vision techniques to analyze facial landmarks and detect patterns associated with drowsiness, such as blinking frequency. The application continuously monitors the driver's facial expressions and provides real-time feedback on their alertness status.

---

**Dependencies:**

To run the Driver Drowsiness Detector, you need the following dependencies:

1. OpenCV (`cv2`)
2. NumPy (`numpy`)
3. dlib (`dlib`)
4. imutils (`imutils`)

Ensure that you have these libraries installed in your Python environment before running the application.

---

**Usage:**

1. **Setup:**
   - Connect a webcam to your computer.
   - Install the required dependencies using `pip install opencv-python numpy dlib imutils`.

2. **Execution:**
   - Run the `drowsiness_detector.py` script.
   - Ensure that your face is clearly visible to the webcam for accurate detection.
   - The application will continuously analyze your facial expressions and display real-time feedback on your alertness status.

3. **Termination:**
   - Press the `Esc` key to exit the application.

---

**Note:**

- This application serves as a tool to raise awareness about drowsy driving and should not be relied upon as the sole means of monitoring driver alertness.
- For optimal performance, ensure proper lighting conditions and minimize distractions during usage.

---

**License:**

- This project is licensed under the [MIT License](LICENSE).


