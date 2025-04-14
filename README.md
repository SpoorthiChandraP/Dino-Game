# 🦖 Hand Gesture Controlled Dino Game

This project allows you to play the **Chrome T-Rex Dino Game** using **hand gestures** detected via webcam! No keyboard required — just show your hand gestures to jump and dodge obstacles!

[![Play the Dino Game](https://img.shields.io/badge/Play%20Dino%20Game-Click%20Here-brightgreen?style=for-the-badge)](https://trex-runner.com/)


## ✨ Features

- 🖐️ Real-time hand gesture detection using **cvzone** and **OpenCV**
- 🎮 Jump in the game by showing a **fist (0 fingers)**
- 🧠 Uses `ctypes` and `SendInput` to simulate keypresses for better compatibility with games
- 🕹️ Works with Chrome Dino game (even offline!)

## 🛠️ Technologies Used

- Python
- OpenCV
- cvzone (built on top of MediaPipe)
- ctypes (for simulating low-level keypresses)
