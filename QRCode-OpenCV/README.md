
# OpenCV QR Code Scanner ( C++ and Python )

**This repository contains the code for [OpenCV QR Code Scanner ( C++ and Python )](https://learnopencv.com/opencv-qr-code-scanner-c-and-python/) blog post**.

[<img src="https://learnopencv.com/wp-content/uploads/2022/07/download-button-e1657285155454.png" alt="download" width="200">](https://www.dropbox.com/sh/195xuwdmt1nbpor/AAAucMK_7Khcch9U9HrLX3iqa?dl=1)

This code requires **OpenCV 3.4.4 or above** or later. 

# For C++

## How to compile the code

Specify the **OpenCV_DIR** in CMake option

```
cmake -D OpenCV_DIR=<path to opencv install directory>/lib/cmake/opencv4/ .
make
```

OR First Specify the **OpenCV_DIR** in CMakeLists.txt file. Then,

```
cmake .
make
```
# How to Run the code

## C++ ##
```
./qrCodeOpencv <filename>
```
## Python ##
```
python qrCodeOpencv.py <filename>
```
**Note** : If you dont give any filename, it will use the default image provided.


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
