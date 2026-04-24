# EcoSort AI 🌍 
> **Smart Waste Segregation using Real-Time Computer Vision**

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![JS](https://img.shields.io/badge/JavaScript-ES6-yellow)
![AI](https://img.shields.io/badge/AI-TensorFlow.js-orange)
![Theme](https://img.shields.io/badge/Hackathon-SIH%202025-blue)

EcoSort AI is a web-based tool designed to solve the problem of improper waste disposal. Built for the **Smart India Hackathon 2025** under the **Clean & Green Technology** theme, it uses a machine learning model to help users identify whether an item belongs in the recycling bin, compost, or landfill.

---

## 📺 Live Demo
*<img width="1916" height="1032" alt="image" src="https://github.com/user-attachments/assets/c4db0f68-6ee4-4f3a-9c1a-a01daf8c0c8a" />
*

## ✨ Key Features
- 🧠 **AI-Powered:** Uses a custom-trained image classification model.
- ⚡ **Real-Time:** Zero-lag detection using the device's webcam.
- 🎨 **Dynamic UI:** The interface changes colors based on the item detected (Green for Recycle, Brown for Compost, Gray for Landfill).
- 🌐 **Browser-Based:** No heavy installation required; works on any modern web browser.

## 🛠️ Tech Stack
- **Languages:** HTML5, CSS3, JavaScript
- **Libraries:** - [p5.js](https://p5js.org/) (Graphics & Webcam)
    - [TensorFlow.js](https://www.tensorflow.org/js) (ML Engine)
    - [Teachable Machine Image Library](https://github.com/googlecreativelab/teachablemachine-community)
- **Model Training:** Google Teachable Machine

## 📂 Project Structure
```text
.
├── index.html       # Main UI structure & library imports
├── style.css        # Custom styling and layout
├── script.js        # Webcam logic and AI model integration
└── README.md        # Documentation
```
## ⚙️ How to Run Locally
* Clone or Download this repository.

Open the folder in VS Code.

Install the Live Server extension.

Right-click index.html and select "Open with Live Server".

Allow camera permissions when prompted by your browser.

## 🤖 The Model
* The model was trained using hundreds of sample images of common household waste.

**Recycle:** *Plastic bottles, soda cans, clean paper, cardboard.*

**Compost:** *Fruit peels, vegetables, coffee grounds.*

**Landfill:**  *Multi-layer packaging (chip bags), styrofoam, soiled tissues.* 
