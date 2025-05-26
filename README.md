# ✋ Real-Time Hand Tracking with MediaPipe & OpenCV

This project demonstrates a real-time **hand tracking and landmark detection system** using **MediaPipe** and **OpenCV** in Python. It captures video from the webcam, detects hand landmarks, and overlays real-time graphics on specific fingers, such as highlighting the thumb tip.

---

## 🎯 Objective

- Detect and track human hands in real-time using a webcam.
- Highlight and visualize specific landmarks like fingertips.
- Measure and display **Frames Per Second (FPS)** to monitor performance.

---

## 📸 Features

- Real-time video capture from webcam
- Hand landmark detection using MediaPipe
- Overlay of connections between hand joints
- Landmark coordinates extraction
- Visual highlight on specific fingers (e.g., thumb tip)
- FPS counter for performance feedback

---

## 🛠️ Technologies & Libraries

- Python 3.x
- [MediaPipe](https://google.github.io/mediapipe/)
- OpenCV

---

## 🧪 How It Works

- `cv2.VideoCapture(0)` captures video from the webcam.
- MediaPipe's `Hands` module processes each frame to detect hand landmarks.
- The system converts BGR images to RGB for MediaPipe processing.
- Detected landmarks are drawn using `mpDraw.draw_landmarks`.
- FPS is calculated and displayed using timestamps.

---

## ▶️ How to Run

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/real-time-hand-tracking.git
cd real-time-hand-tracking
````

2. **Install Dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Application**

```bash
python hand_tracking.py
```

4. **Exit**

* Press **Enter** (Key code 13) to close the webcam feed.

---

## 📁 Files to Include

```
real-time-hand-tracking/
│
├── hand_tracking.py            # Main Python script
├── requirements.txt            # Required Python libraries
├── README.md                   # Project documentation
└── example_output.png          # (Optional) Screenshot of app in action
```

---

## 📦 requirements.txt

```txt
opencv-python
mediapipe
```

---

## 📌 Example Code Snippet

```python
if id == 4:
    cv2.circle(img, (cx, cy), 20, (255, 0, 255), cv2.FILLED)
```

This highlights the **thumb tip** when detected.

---

## 🔮 Future Enhancements

* Gesture recognition (e.g., counting fingers)
* Trigger actions based on gestures
* Integration with GUI or games
* Combine with voice commands or sensors

---

## 👨‍💻 Author

**Ankit Kumar**
🎓 B.Tech – Artificial Intelligence & Data Science
🏫 Truba Institute of Engineering and Information Technology
📍 Bhopal, Madhya Pradesh


---

## 📜 License

This project is licensed under the **MIT License**.

---

⭐ If you find this project helpful, please star the repository and share it!

````

---

## ✅ `requirements.txt`

```txt
opencv-python
mediapipe
````

---

