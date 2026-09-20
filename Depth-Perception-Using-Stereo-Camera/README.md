
# Depth Estimation using Stereo Camera and OpenCV

**This repository contains code for [Depth Estimation using Stereo Camera and OpenCV](https://learnopencv.com/depth-perception-using-stereo-camera-python-c/) blogpost**.

[<img src="https://learnopencv.com/wp-content/uploads/2022/07/download-button-e1657285155454.png" alt="download" width="200">](https://www.dropbox.com/sh/cl70ubt31ya0e64/AABA77qwIX8rFiclw8drdPSXa?dl=1)

Create a custom low-cost stereo camera and capture depth maps with it using OpenCV.

## Directory Structure
**All the code files and folders follow the following structure.**

```
├── cpp
│   ├── disparity2depth_calib.cpp
│   ├── disparity_params_gui.cpp
│   ├── obstacle_avoidance.cpp
│   └── CMakeLists.txt
├── data
│   ├── depth_estimation_params.xml
│   ├── depth_estimation_params_cpp.xml
│   ├── depth_estmation_params_py.xml
│   ├── depth_params.xml
│   └── stereo_rectify_maps.xml
├── python
│   ├── disparity2depth_calib.py
│   ├── disparity_params_gui.py
│   ├── obstacle_avoidance.py
│   └── requirements.txt
└── README.md
```

## Instructions

### C++

To run the code in C++, please go into the `cpp` folder, then compile the `disparity_params_gui.cpp`, `obstacle_avoidance.cpp` and `disparity2depth_calib.cpp` code files, use the following:

```shell
mkdir build
cd build
cmake ..
cmake --build . --config Release
```

### Use the following commands to execute the compiled files:


```shell
./build/disparity_params_gui
./build/disparity2depth_calib
./build/obstacle_avoidance
```


### Python

To run the code in Python, please go into the `python` folder and refer to the following to use the `disparity_params_gui.py`, `obstacle_avoidance.py` and `disparity2depth_calib.py` files respectively:

```shell
python3 disparity_params_gui.py
python3 disparity2depth_calib.py
python3 obstacle_avoidance.py
```


---

<p align="center">
  <a href="https://bigvision.ai/">
    <img src="https://bigvision.ai/logos/logo.png" alt="BigVision.AI" width="300">
  </a>
</p>

<h2 align="center">Build Production-Ready Computer Vision &amp; AI Solutions</h2>

<p align="center">
  LearnOpenCV is maintained by <a href="https://bigvision.ai/"><strong>BigVision.AI</strong></a>, a computer vision and AI consulting company. We help organizations design, build, optimize, and deploy production-ready AI solutions. Our team has deep expertise in computer vision, deep learning, multimodal AI, and edge deployment, with experience solving complex technical challenges across industries.
</p>

<p align="center">
  Have a project in mind? Talk with our expert AI solution builders.
</p>

<p align="center">
  <a href="https://bigvision.ai/expert-ai-solution-builders?utm_source=locv-github">
    <img src="https://img.shields.io/badge/Get%20in%20Touch-087EA4?style=for-the-badge" alt="Get in Touch with BigVision.AI">
  </a>
</p>
