# Driver Drowsiness Detection System 🚗💤

A **real-time driver drowsiness detection system** that monitors driver fatigue using computer vision techniques and provides timely alerts to prevent accidents. Built using Python, OpenCV, and Mediapipe.

---

## Features

- **Real-Time Eye & Mouth Monitoring**  
  Uses **Mediapipe Face Mesh** to detect facial landmarks and calculate:
  - **EAR (Eye Aspect Ratio)** – detects eye closure
  - **MAR (Mouth Aspect Ratio)** – detects yawning

- **Drowsiness Alerts**  
  - Triggers visual and audio alerts when the driver shows signs of fatigue.
  - Supports **cross-platform alarms** using `winsound` on Windows or `playsound`.

- **Configurable Parameters**  
  - Eye and mouth thresholds (`EAR_THRESHOLD`, `MAR_THRESHOLD`)
  - Consecutive frame counts to reduce false positives
  - Easy to tweak for different camera setups or lighting conditions

- **Lightweight & Efficient**  
  - Runs on a standard webcam
  - Optimized for real-time detection without heavy hardware

---

## Tech Stack

- **Programming Language:** Python 3.10
- **Libraries & Frameworks:**  
  - `OpenCV` – Real-time video capture and image processing  
  - `Mediapipe` – Facial landmark detection  
  - `NumPy` – Numerical computations  
  - `math` – Euclidean distance calculations  
  - `playsound` / `winsound` – Cross-platform audio alerts  

