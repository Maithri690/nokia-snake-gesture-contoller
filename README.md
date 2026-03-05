# 🐍 Nokia Snake Game – Hand Gesture Controller

## 📌 Project Overview

The **Nokia Snake Game – Hand Gesture Controller** is an interactive computer vision project that allows users to control the classic snake game using **hand gestures instead of a keyboard**. The system uses a webcam to detect hand movements and translate them into game controls.

This project combines **computer vision, real-time hand tracking, and game development** to create a fun and innovative way to play the nostalgic Nokia snake game.

---

## 🎯 Objectives

* Recreate the classic Nokia Snake Game.
* Control the snake using **hand gestures detected by a webcam**.
* Demonstrate real-time **gesture recognition using computer vision**.
* Provide a touchless gaming experience.

---

## 🛠️ Technologies Used

* **Python**
* **OpenCV** – for video processing
* **MediaPipe** – for hand tracking and gesture detection
* **NumPy** – for numerical computations
* **Pygame** – for game development and rendering

---

## ⚙️ Features

* 🎮 Classic Snake Game gameplay
* ✋ Hand gesture control for movement
* 📷 Real-time webcam input
* ⚡ Fast gesture recognition
* 🧠 Computer vision-based interaction
* 🎯 Score tracking system

---

## 🧩 How It Works

1. The webcam captures live video.
2. Hand tracking detects the user's hand using MediaPipe.
3. The system identifies the direction of the hand gesture.
4. The detected gesture is converted into snake movement.
5. The snake moves on the game screen accordingly.

---

## 🚀 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Maithri690/nokia-snake-gesture-contoller.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd nokia-snake-gesture-contoller
```

### 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python main.py
```

Make sure your **webcam is enabled** before running the program.

---

## 🎮 Hand Gesture Controls

| Gesture Direction | Snake Movement    |
| ----------------- | ----------------- |
| Move Hand Up      | Snake Moves Up    |
| Move Hand Down    | Snake Moves Down  |
| Move Hand Left    | Snake Moves Left  |
| Move Hand Right   | Snake Moves Right |

---

## 📂 Project Structure

```
nokia-snake-gesture-contoller
│
├── main.py
├── snake_game.py
├── hand_tracking.py
├── requirements.txt
└── README.md
```

---

## 📈 Future Improvements

* Add gesture-based **pause and restart controls**
* Improve gesture accuracy
* Add different difficulty levels
* Add multiplayer gesture mode
* Deploy the game as a web application

---

## 👩‍💻 Author

**Maithri**

---

## ⭐ Acknowledgements

* Inspired by the **classic Nokia Snake Game**
* Thanks to open-source libraries and the computer vision community.
