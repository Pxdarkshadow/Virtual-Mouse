# 🖱️ Virtual Mouse using OpenCV and Hand Tracking

A Python-based virtual mouse that lets you control your computer cursor with hand gestures using your webcam. This project utilizes OpenCV for image processing, MediaPipe for real-time hand tracking, and PyAutoGUI to simulate mouse actions.

![Demo Screenshot](./screenshots/demo.png) 

![Screenshot 2025-04-28 213314](https://github.com/user-attachments/assets/2749692b-8498-4314-b9ae-4f0354d3e869)


## ✨ Features

- 🖐️ Hand tracking with high accuracy using MediaPipe
- 🖱️ Cursor movement using index finger
- 👆 Left click with index + middle finger pinch
- 🤏 Right click with index + ring finger pinch
- 🔄 Extendable for scroll and drag gestures

---

## 🛠️ Tech Stack

- **Python 3.8+**
- **OpenCV** – for video capture and processing
- **MediaPipe** – for hand landmark detection
- **PyAutoGUI** – for mouse control

---

## 📦 Requirements

You can install all dependencies with:

```bash
pip install -r requirements.txt
````

```bash
pip install opencv-python mediapipe pyautogui
```

---

## 🚀 How to Run

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/virtual-mouse-opencv.git
cd virtual-mouse-opencv
```

2. **Run the Script**

```bash
python virtual_mouse.py
```

Make sure your webcam is connected and accessible.

---

## ✋ How it Works

* The webcam feed is processed frame by frame using OpenCV.
* MediaPipe detects and tracks 21 hand landmarks.
* Coordinates of the index finger tip are used to move the cursor.
* Distance between specific fingers determines click actions:

  * **Left Click:** Pinch index and middle fingers
  * **Right Click:** Pinch index and ring fingers

---

## 📂 Project Structure

```
virtual-mouse/
│
├── virtual_mouse.py       # Main Python script
├── README.md              # Project readme 
├── requirements.txt       # Python package dependencies
└── screenshots/        
```

---

## 📸 Demo

Watch the original tutorial by Murtaza’s Workshop:

🔗 [YouTube Video](https://youtu.be/4NmwNEYtL1s?si=AFcWWKczN0NP4UwO)

---

## 🙌 Credits

Built based on the tutorial by [Murtaza’s Workshop - Robotics and AI](https://www.youtube.com/@MurtazasWorkshop).

---

## 📄 License

This project is licensed under the MIT License. Feel free to use and modify for learning purposes.

---

## 📬 Contact

If you have questions or improvements, feel free to raise an issue or contribute via pull request.

```

```
