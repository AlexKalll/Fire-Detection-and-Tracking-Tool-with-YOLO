# Fire Detection and Tracking Tool Using YOLOv8

**Welcome👋 to my object detection and video stream tracking Project given by [CodeAlpha](https://codealpha.tech)**
## Overview

This project implements a **Fire Detection and Tracking Tool** using the YOLOv8 (You Only Look Once) object detection algorithm. The tool allows users to perform live detection through a webcam or analyze static images for fire detection. The model has been trained using a dataset obtained from Roboflow.

## Introduction

YOLO is a state-of-the-art, real-time object detection system that can detect multiple objects in images and videos. This project focuses on detecting fire in various environments, making it useful for safety applications.

## Requirements

To run this project, ensure you have the following installed:

- Python 3.8 or higher
- OpenCV
- PyTorch
- Ultralytics YOLOv8

You can install the required packages using:
`pip install opencv-python torch torchvision ultralytics`
`pip install numpy pandas matplotlib` 
(The second one is optional since they are dependencies, they will be installed by default when you install the required packages.)

**Setup**
1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/fire-detection-yolo.git
2. Navigate to the desired directory.
    ```bash
    cd fire-detection-yolo
3. Download the trained model best.pt from your Google Colab environment and place it in the project directory.

### Usage
Run the script using:
    `python main.py`

You will be prompted to choose between live detection or static image prediction:

1. Enter `live` for live webcam detection. Then your camera will be opened for detection. Press `q` to exit the live feed.

2. Enter `static` for analyzing a static image. Provide the path to the image file when prompted, and the model will process the image for fire detection. Finally, the model the detected image or video will be saved in the `runs\detects` directory(actually it depends on the path you defined when you build your model).

# Acknowledgnments
A special thanks to Roboflow for providing the datasets used to train the YOLOv8 model. Their platform simplifies the process of dataset management and model training, making it easier for developers to build robust AI solutions.

Mainly, I just wanted to take a moment to express my **heartfelt gratitude** to **[CodeAlpha](https://codealpha.tech)** for providing me with an incredible internship opportunity in the feilf of `AI/ML/DL`! 🙌✨

This experience has been nothing short of amazing, and I have learned so much! 📚💡
Thank you for believing in me and giving me the chance to grow both personally and professionally. 🌱💪

I’m truly grateful for this opportunity! Here’s to more learning and growth ahead! 🚀🌟

**Thank you, [CodeAlpha](https://codealpha.tech)!** 💖🙌🎉


### Contact me
[LinkedIn](https://www.linkedin.com/in/kaletsidik-ayalew-mekonnen-34772226b/) | [Instagram](https://www.instagram.com/kaletsidik.24?igsh=YzljYTk1ODg3Zg==) | [X~Twitter](https://x.com/kaletsidike?t=VCe79O084EmE9bM2V5jOIA&s=09) | [Telegram](https://t.me/Adragon_de_mello) | [GitHub](https://github.com/AlexKalll) | [LeetCode](https://leetcode.com/Alexkal/)


Kaletsidik Ayalew
alexkalalw@gmail.com