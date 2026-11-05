Gesture-Controlled Snake Game

An interactive, computer-vision-powered take on the classic retro arcade game! This project replaces traditional keyboard inputs with **real-time hand gesture tracking**, allowing you to steer the snake using your index finger through your webcam.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Game Engine:** Pygame-CE (Community Edition)
* **Computer Vision & Tracking:** OpenCV & MediaPipe Tasks API

---

## ✨ Features
* **Real-Time Hand Tracking:** Uses Google's MediaPipe machine learning model to track hand landmarks and fingertip coordinates live.
* **Hands-Free Control:** Maps your hand positioning relative to webcam quadrants to issue `UP`, `DOWN`, `LEFT`, and `RIGHT` directional commands.
* **Smart Navigation Filter:** Includes dead zones and reverse-turn checks to ensure smooth, stable gameplay without accidental self-collisions.
* **Classic Arcade Mechanics:** Features dynamic food generation, boundary/self-collision checks, live scoring, and an interactive restart option.
