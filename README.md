# 🎨 Virtual Art Board – Draw with Hand Gestures

> Create digital art with your hands! ✋🖌️  
> A **real-time gesture-controlled drawing system** using **Python**, **OpenCV**, and **MediaPipe**.  
> Your hand becomes the brush — no stylus or touchscreen required!

---

## 🧠 Overview

The **Virtual Art Board** transforms human hand movements into digital brush strokes in real-time using computer vision.  
By detecting hand landmarks through a webcam, it enables **air drawing**, color selection, and live brush movement — making creativity more natural and intuitive.

---

## 🚀 Features

✅ Real-time hand tracking using **MediaPipe**  
✅ Draw using index finger movements  
✅ Multiple brush colors  
✅ Gesture-based color selection  
✅ Adjustable brush thickness  
✅ Save your artwork as images  
✅ Clear canvas instantly  
✅ FPS counter for smooth performance  
✅ Works with any webcam — no external device needed  

---

## 🧰 Tech Stack

| Technology | Usage |
|-------------|--------|
| **Python 3.8+** | Core programming |
| **OpenCV** | Real-time video and drawing |
| **MediaPipe** | Hand tracking and gesture recognition |
| **NumPy** | Image processing and matrix operations |

---

## 🧩 System Workflow

1️⃣ Capture hand movements via webcam  
2️⃣ Detect and track 20+ hand landmarks  
3️⃣ Identify gestures (e.g., index finger up = draw)  
4️⃣ Render strokes on a blank canvas in real time  
5️⃣ Save or clear canvas with keyboard shortcuts  

---

## 🖥️ Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/virtual-art-board.git

# Navigate to project folder
cd virtual-art-board

# Install dependencies
pip install -r requirements.txt

# Run the project
python virtual_art_board.py
