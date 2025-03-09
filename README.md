# 🎨 Air Canvas with Machine Learning

## ✨ Overview
Ever wanted to draw your imagination by just waving your finger in the air? 🖐️✨ This project, **Air Canvas**, allows you to draw on a virtual canvas using hand gestures! We leverage **OpenCV** and **Mediapipe** to track hand landmarks and translate movements into digital drawings. A perfect project to showcase on your resume for **machine learning and computer vision enthusiasts**! 🚀

## 🛠️ Technologies Used
- **Python 🐍** (preferred for its ease of use and extensive libraries)
- **OpenCV 🎥** (for image processing)
- **Mediapipe 🤖** (for hand tracking)
- **NumPy 🔢** (for handling arrays and computations)

## 📌 Features
- 🖐️ **Hand Landmark Detection** using Mediapipe
- ✏️ **Draw on a Virtual Canvas** with just finger movements
- 🎨 **Multiple Colors** selection using on-screen buttons
- 📷 **Real-time Processing** using OpenCV
- 🖥️ **Customizable Interface** with easy-to-modify parameters

## ⚙️ Algorithm
1. 📸 **Capture frames** from the webcam and convert them to **HSV color space** (for easier color detection).
2. 🎨 **Prepare the canvas** and overlay ink buttons.
3. 🛠️ **Initialize Mediapipe** to detect **only one hand**.
4. 🖐️ **Detect hand landmarks** by passing the RGB frame to the Mediapipe hand detector.
5. 📍 **Extract forefinger coordinates** and store them in an array for successive frames.
6. ✏️ **Draw the stored points** on the canvas and display the output.

## 📋 Requirements
Ensure you have the following installed:
```bash
pip install opencv-python mediapipe numpy
```

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Muskaanng/Air-Canvas.git
   cd Air-Canvas
   ```
2. Run the script:
   ```bash
   python air_canvas.py
   ```


## 🛠️ Customization
- Adjust **drawing thickness**, **colors**, and **canvas size** in the script.
- Modify the **Mediapipe parameters** to fine-tune hand detection.

## 🤝 Contributing
Pull requests are welcome! Feel free to open issues for any feature requests or improvements. 😊



<img src="" width="950" height="400">
