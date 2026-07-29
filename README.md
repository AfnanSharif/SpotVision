<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=8E2DE2,4A00E0&height=200&section=header&text=SpotVision&fontSize=70&fontColor=ffffff&animation=twinkling" width="100%" />

<img src="https://img.icons8.com/?id=43604&format=png&size=100" width="90" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2500&pause=1000&color=8E2DE2&center=true&vCenter=true&width=700&height=50&lines=Zone-Based%20Object%20Detection;YOLOv8%20+%20OpenCV" alt="Typing SVG" />

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-00FFFF?style=for-the-badge)](#)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)](#)
[![License](https://img.shields.io/github/license/AfnanSharif/SpotVision?style=for-the-badge&color=yellow)](LICENSE)

</div>

---

## 📖 Overview

**SpotVision** runs a YOLOv8 model over a video feed and checks whether detected objects fall
inside user-defined polygon zones (`is_point_in_polygon`) — useful for zone intrusion / area
monitoring use cases.

## 🏗️ Project Layout

```
SpotVision/
├── main.py          # Entry point — loads the YOLOv8 model and processes video
├── functions.py        # Polygon geometry + object helpers
├── Models/                # Trained YOLOv8 weights
└── requirements.txt
```


## ⚡ Setup & Run

### 🪟 Windows / 🍎 macOS / 🐧 Linux
```bash
git clone https://github.com/AfnanSharif/SpotVision.git
cd SpotVision

python -m venv venv
# Windows: venv\Scripts\activate | macOS/Linux: source venv/bin/activate
pip install -r requirements.txt

python main.py
```

---

<div align="center">

**Created by [AfnanSharif](https://github.com/AfnanSharif)** · ⭐ star this repo if it helped you

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=8E2DE2,4A00E0&height=80&section=footer" width="100%" />

</div>
