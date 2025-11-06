 🖐️ Hand Gesture Volume Control using Python

 🎯 Overview

This project allows users to **control system volume using hand gestures** detected through a webcam.  
By leveraging **computer vision** and **AI-powered hand tracking**, it converts the distance between two fingers (thumb and index) into volume level commands — creating a smooth, touch-free way to interact with your computer.

---

 🧩 Key Idea

- The webcam captures your hand in real-time.
- **MediaPipe** detects hand landmarks (specific key points like finger tips and joints).
- The **distance between the thumb tip and index fingertip** is continuously measured using Euclidean distance.
- Based on that distance:
  - When fingers are **far apart → Volume increases** 🔊  
  - When fingers are **close together → Volume decreases** 🔉  
- **PyAutoGUI** simulates the volume key presses to change the system volume automatically.

---

 🧠 Concepts Used

| Concept | Description |
|----------|--------------|
| **Computer Vision** | Processing real-time video feed from the webcam. |
| **Hand Landmark Detection** | Using MediaPipe to find 21 key points on the hand. |
| **Euclidean Distance** | Measuring distance between thumb and index fingertips. |
| **Gesture Recognition** | Mapping specific gestures to volume control actions. |
| **Human–Computer Interaction (HCI)** | Creating a natural, gesture-based interface. |

---

 ⚙️ Features

✅ Real-time hand detection using your webcam  
✅ Volume adjustment based on gesture distance  
✅ Works without additional hardware  
✅ Lightweight and cross-platform (Windows, macOS, Linux)  
✅ Built entirely with open-source Python libraries  

---

🛠️ Tech Stack

| Library | Purpose |
|----------|----------|
| `OpenCV` | Capture and process webcam images |
| `MediaPipe` | Detect and track hand landmarks |
| `PyAutoGUI` | Control system volume through keyboard shortcuts |
| `NumPy` | Perform mathematical calculations on landmark coordinates |

---

📸 Demo Preview

![Hand Volume Control Demo](Images/demo.png)

💡 Applications

Touchless gesture control interfaces

Accessibility tools for differently-abled users

Integration with smart home or IoT systems

Educational computer vision projects

🧑‍💻 Author

👤 Tufail Nalband
💻 Python & AI Enthusiast | Computer Vision Developer


