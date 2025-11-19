# WebXR AR Model Viewer (XRGestures Test)

A small WebXR test project that lets you place and manipulate **3 preloaded 3D models in Augmented Reality** using **gesture controls** (tap, pan, pinch, rotate, swipe) on supported mobile devices.

🔗 **Live Demo:** https://web-xr-x-rgestures-test.vercel.app  
👤 **Author:** [Yousuf Mohammad Amin](https://github.com/y-m-amin)

> ⚠️ **Important:**  
> This project only works on **phones that support WebXR-based Augmented Reality** (e.g. compatible Android devices using Chrome).  
> Desktop browsers and unsupported phones will **not** be able to enter AR mode.

---

## ✨ Features

- 🧱 **Three preloaded 3D models** selectable from a dropdown
- 📱 **AR placement** of models on real-world surfaces
- 🖐️ **Gesture controls** via [XRGestures](https://github.com/NikLever/XRGestures/tree/main):
  - **Tap** – place/show model
  - **Pan** – move model across the surface
  - **Pinch** – scale model up/down
  - **Rotate** – rotate model around Y-axis
  - **Swipe** – hide/remove model
- 💡 **Physically-based lighting** using HDR environment map
- 🧩 Built with **Three.js**, **GLTFLoader**, **ARButton**, and **CanvasUI**

---

## 🧰 Tech Stack

- [Three.js](https://threejs.org/)
- WebXR 
- `XRGestures` for gesture recognition

---

## 📦 Getting Started (Local Setup)

> ℹ️ This project is a static WebXR experience using ES modules.  
> You must serve it over **HTTP/HTTPS** with a simple dev server (opening `index.html` directly from the file system will not work properly).

### 1. Clone the Repository

```bash
git clone https://github.com/y-m-amin/WebXR-XRgestures-test.git
cd web-xr-xrgestures-test
```
