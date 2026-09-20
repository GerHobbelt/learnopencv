# Hough Transform with OpenCV in C++ and Python

**This repository contains the code for [Hough Transform with OpenCV (C++/Python)](https://learnopencv.com/hough-transform-with-opencv-c-python/) blog post**.

[<img src="https://learnopencv.com/wp-content/uploads/2022/07/download-button-e1657285155454.png" alt="download" width="200">](https://www.dropbox.com/sh/1ovla44mpet4p99/AAA0mQCg_mWDFpy2CbeJQoSia?dl=1)

### Hough Line Transform

**Usage**

**Python**

- ```python3 hough_lines.py lanes.jpg```

**C++**

- ```g++ hough_lines.cpp `pkg-config opencv --cflags --libs` -o hough_lines```
- ```./hough_lines lanes.jpg```

**CMake**

- ```mkdir build```
- ```cd build```
- ```cmake ..```
- ```cmake --build . --config Release```
- ```cd ..```
- ```./build/hough_lines lanes.jpg```

### Hough Circle Transform

**Usage**

**Python**

- ```python3 hough_circles.py brown-eyes.jpg```

**C++**

- ```g++ hough_circles.cpp `pkg-config opencv --cflags --libs` -o hough_circles```
- ```./hough_circles brown-eyes.jpg```

**CMake**

- ```mkdir build```
- ```cd build```
- ```cmake ..```
- ```cmake --build . --config Release```
- ```cd ..```
- ```./build/hough_circles brown-eyes.jpg```


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
