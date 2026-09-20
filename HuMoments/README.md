# Shape Matching using Hu Moments (C++/Python)

**This repository contains the code for [Shape Matching using Hu Moments (C++/Python)](https://learnopencv.com/shape-matching-using-hu-moments-c-python/) blog post**.

[<img src="https://learnopencv.com/wp-content/uploads/2022/07/download-button-e1657285155454.png" alt="download" width="200">](https://www.dropbox.com/sh/b6idgsj9uu078il/AAB-sNX6J0MBf0Wwizjo17VPa?dl=1)

This directory also contains code for using Hu Moments to match shapes.

# For C++

## How to compile the code
If you don't have OpenCV installed globally, then Specify the **OpenCV_DIR** in CMakeLists.txt file. Then,

```
cmake .
make
```
# How to Run the code

## C++ ##
## Find Hu Moments
```
./HuMoments images/*
```

## Match shapes
```
./shapeMatcher
```


## Python ##
## Find Hu Moments
```
python HuMoments.py images/*
```

## Match shapes
```
python shapeMatcher.py
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
