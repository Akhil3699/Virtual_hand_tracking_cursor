## Hand Gesture Controlled Virtual Mouse

This Python program utilizes MediaPipe and PyAutoGUI to create a hand gesture-controlled virtual mouse. By detecting hand landmarks through a webcam feed, it allows users to control the mouse cursor and perform actions such as clicking, right-clicking, and adjusting volume with hand gestures.

### Requirements:

1. **Python:** Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/) [Version 3.8 recommended]

2. **OpenCV:** Install the OpenCV library for Python. You can install it using pip:
   ```
   pip install opencv-python
   ```

3. **MediaPipe:** Install the MediaPipe library for Python. You can install it using pip:
   ```
   pip install mediapipe
   ```

4. **PyAutoGUI:** Install the PyAutoGUI library for Python. You can install it using pip:
   ```
   pip install pyautogui
   ```

### How to Use:

1. **Run the Program:**
   - Open a terminal or command prompt.
   - Navigate to the directory containing the Python script.
   - Run the script using the following command:
     ```
     python hand_gesture_mouse.py
     ```

2. **Hand Gesture Control:**
   - Once the program is running, it will utilize your webcam feed.
   - Perform hand gestures in front of the webcam to control the virtual mouse cursor.
   - The program detects landmarks on your hand and translates them into mouse movements.
   - Different gestures trigger various actions such as clicking, right-clicking, and adjusting volume.


### Notes:

- The program uses MediaPipe to detect hand landmarks and PyAutoGUI to control the mouse cursor.
- Hand gestures such as moving your index finger control the cursor movement, while gestures like closing your hand trigger clicking actions.
- Ensure proper lighting and hand visibility for accurate gesture detection.
- Adjustments to gesture sensitivity and actions can be made by modifying the code as needed.

**Help me out with the "Drag and Drop" feature if you can**
Feel free to contribute to the program!!!
