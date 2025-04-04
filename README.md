# 🧠 WaveVol - Hands-Free Volume Control using Computer Vision

WaveVol is an innovative system that allows users to control their system's audio volume using **hand gestures**. Built using **computer vision** and **deep learning**, this project aims to provide a hands-free alternative for physically impaired individuals, while laying the foundation for more advanced gesture-based interfaces like **sign language navigation**.

---

## 📌 Features

- 📷 Real-time hand detection using **MediaPipe Hands**
- 🤖 Distance estimation between fingers to map volume level
- 🔊 System volume adjustment using **pycaw** (Windows audio control)
- 🧠 Designed for accessibility, built for innovation

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/MediaPipe-ff6f00?style=for-the-badge&logo=mediapipe&logoColor=white" />
  <img src="https://img.shields.io/badge/PyCaw-003B57?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-FA0F00?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

---

## ⚙️ How It Works

1. **Hand Detection**:
   - The system captures frames from your webcam using **OpenCV**.
   - Using **MediaPipe Hands**, it detects and tracks your hand landmarks in real-time.

2. **Gesture Recognition**:
   - Specifically monitors the distance between the **thumb and index finger**.
   - The shorter the distance, the lower the volume; the greater the distance, the higher the volume.

3. **Volume Mapping**:
   - Converts the finger distance into a volume level between 0 and 100.
   - Adjusts system volume via **pycaw** based on this mapping.

---

## 🚀 Usage Instructions

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/WaveVol.git
cd WaveVol
```

2. **Install Requirements**
```bash
pip install -r requirements.txt
```

3. **Run the Notebook**
Open `gesture.ipynb` and run all cells, or convert to script as needed.

---

## 🧩 Potential Applications

- Accessibility tools for users with physical impairments
- Touchless interfaces for smart homes
- Gesture-based control in VR/AR environments
- **Future extension**: Sign language recognition to control applications

---

## 🔭 Future Work (In Progress 🚧)

I'm actively working on extending WaveVol beyond basic gestures. Here's what’s coming up:

- **Sign Language Recognition**: Building models to recognize full sign language gestures for broader system interaction.
- **Web Navigation**: Enabling users to navigate web pages using sign gestures (scroll, click, search).
- **Custom Command Mapping**: Users can train the system with their own gestures for specific actions.
- **Cross-platform Support**: Making WaveVol compatible with macOS and Linux (currently optimized for Windows).
- **Deployment with GUI**: A lightweight desktop app interface for ease of use.

This is part of a larger mission to make **gesture-based accessibility tools** mainstream and impactful.

---

## 🙌 Contribute

Have an idea or want to extend this to full sign language recognition? Fork it, build it, and open a pull request! 🤝

---

Made with ❤️ to make tech more inclusive.

