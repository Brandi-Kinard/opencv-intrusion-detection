# OpenCV Intrusion Detection System
<a target="_blank" href="https://colab.research.google.com/github/Brandi-Kinard/opencv-intrusion-detection/blob/main/Intrusion_Detection_Application.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Overview
Welcome to the repository of the OpenCV Intrusion Detection System, a sophisticated tool designed to enhance security by monitoring surveillance video streams for unusual activities. This system not only identifies intrusions but also archives relevant video segments for further analysis and can trigger alerts to notify security personnel.

<img width="1267" alt="image" src="https://github.com/Brandi-Kinard/opencv-intrusion-detection/assets/52756042/70c02253-2659-4c75-9526-617c73683890">



## Why This Project is Important
In today's world, the safety and security of physical spaces are paramount. This project leverages computer vision and machine learning to provide a vigilant, always-on watch over sensitive areas, ensuring that any unusual activity is promptly detected and addressed. It's particularly useful in settings such as banks, stores, and private properties.

## How It Works
- **Background Subtraction**: Uses `createBackgroundSubtractorKNN()` to differentiate moving objects from the static background.
- **Noise Reduction**: Applies erosion to the foreground masks to minimize noise, ensuring that motion detection is accurate.
- **Motion Detection**: Analyzes the shapes in the video via `findContours()` to capture the contours of moving objects.
- **Intrusion Identification**: Identifies potential intrusions by assessing the size and location of the largest moving object.
- **Alerts and Record-Keeping**: When an intrusion is detected, the system saves the relevant video segment and can trigger an alert.

## How to Use This Project
To get started with this motion detection notebook:
1. Clone this repository to your local machine using `git clone https://github.com/Brandi-Kinard/opencv-intrusion-detection.git`
2. Ensure you have Jupyter Notebook installed, or use **Google Colab** (accessible via the "Open in Colab" badge above) to open the notebook.
3. Install necessary libraries (listed in the Prerequisites section below).
4. Run the notebook cells sequentially to observe motion detection in action.

## Prerequisites
Ensure you have the following installed:

- Python 3.6+
- OpenCV (opencv-python)
- Matplotlib
- IPython (for Jupyter functionality)
- Moviepy
- Imageio
- Numpy

Install these packages using pip:
```bash
pip install opencv-python matplotlib ipython moviepy numpy imageio
```

## For the Future
If you want to add more, Please don't hesitate to open a [pull request](https://github.com/Brandi-Kinard/opencv-intrusion-detection/pulls).

## 👋 Get in Touch
[![text](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brandi-kinard)
