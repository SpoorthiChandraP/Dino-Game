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

## 📋 How to Use / Instructions

1. Open Google Chrome.

2. Visit the game at: https://trex-runner.com/ (Alternatively, type chrome://dino in the address bar and hit Enter)

3. Make sure the game window is in focus (click on it once).

4. Run the main Python script: python main.py
Make sure your webcam is active and clearly sees your hand.

5. Use hand gestures:

✊ Fist (0 fingers up) → Dino jumps

✋ Any other gesture (1–5 fingers) → No action

✅ Tip: Keep your hand within the frame and use a well-lit background for best results.
