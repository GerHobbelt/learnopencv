# Image Quality Assessment : BRISQUE
The repository contains code for the blog post [Image Quality Assessment : BRISQUE](https://learnopencv.com/image-quality-assessment-brisque/).

<img src="https://learnopencv.com/wp-content/uploads/2018/06/workflow-brisque-iqa.png" alt="BRISQUE" width="900">

[<img src="https://learnopencv.com/wp-content/uploads/2022/07/download-button-e1657285155454.png" alt="download" width="200">](https://www.dropbox.com/scl/fo/n19a8fzvboq1nwhnbeh3y/h?dl=1&rlkey=za90lmxl5pq49i2qlyuv07t00)

## Installation Instructions
**Python 2.x LIBSVM Installation**
`sudo apt-get install python-libsvm`

**Python 3.x LIVSVM Installation and C++ LIBSVM Installation**

For C++ :

1. `cd C++/libsvm/`
2. `cmake .`
3. `make`

For Python 3.x :

1. `cd Python/libsvm/`
2. `make`
3. `cd python`
4. `make`

## Usage 

**Python 2.x**

1. `python2 brisquequality.py <image_path>`

**Python 3.x** 

1. `cd Python/libsvm/python/`
2. `python3 brisquequality.py <image_path>`

**C++**

1. `cd C++/`
2. `./brisquequality <image_path>`


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
