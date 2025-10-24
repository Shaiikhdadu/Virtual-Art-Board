# 🎨 Virtual Art Board – Hand Gesture Controlled AI Drawing System

> **Hands in the Air → Art on the Screen** ✋🖌️  
> Real-time gesture-based digital art using **Python**, **OpenCV**, & **MediaPipe**.

---

### 🏷️ Badges

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-ComputerVision-green)
![MediaPipe](https://img.shields.io/badge/MediaPipe-HandTracking-orange)
![Issues](https://img.shields.io/github/issues/Shaiikhdadu/virtual-art-board)
![Stars](https://img.shields.io/github/stars/Shaiikhdadu/virtual-art-board)
![Forks](https://img.shields.io/github/forks/Shaiikhdadu/virtual-art-board)
![License](https://img.shields.io/badge/License-MIT-purple)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=flat)
![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red)

---

## 🧠 Overview
The **Virtual Art Board** transforms hand gestures into digital brush strokes using a webcam.  
It detects hand landmarks with MediaPipe and enables a natural, touchless drawing experience.

---

## 🚀 Features

| Feature | Status |
|--------|:-----:|
| Real-time gesture tracking | ✅ |
| Color selection using fingertip | ✅ |
| Brush drawing with index finger | ✅ |
| Save artwork as image | ✅ |
| Canvas clearing | ✅ |
| Drawing pause/resume | ✅ |
| FPS counter | ✅ |

---

## 🧰 Tech Stack

| Technology | Role |
|-----------|------|
| Python | Base Programming |
| OpenCV | Image + Rendering |
| MediaPipe | AI Hand Detection |
| NumPy | Pixel Data Processing |

---

## 🎮 Controls

| Key | Function |
|-----|----------|
| **S** | Save drawing |
| **C** | Clear canvas |
| **H** | Toggle draw mode |
| **Q / ESC** | Quit application |

---

## 🛠️ Installation

```bash
git clone https://github.com/Shaiikhdadu/virtual-art-board.git
cd virtual-art-board
pip install -r requirements.txt
python Main.py


✅ Webcam required
✅ Python 3.8+ recommended

🧩 How It Works
📌 Detects 21 hand landmarks using AI
✋ Gesture checks → Thumb & index finger contact = Draw Mode
🎯 Index fingertip coordinates map to canvas
🎨 Touch corner circles to change brush colors
📷 Demo
< i am uploading the Sample ScreenShots in a seperate file named "SampleScreenShots">

🔮 Future Roadmap
 Eraser gesture ✊
 Brush size gesture (pinch zoom)
 Multi-hand drawing
 Shapes & stamps
 UI-based toolbar
 Save artwork with transparency

🤝 Contributing
Pull requests are welcome!
Fork → Improve → PR 🚀
📜 License
Released under MIT License ✅
👨‍💻 Author
Shaikh Dadu
🔗 GitHub: Shaiikhdadu
