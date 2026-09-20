# Center of Blob using Python and CPP

This repository contains code for the blog post [Find the Center of a Blob using OpenCV (C++/Python)](https://learnopencv.com/find-center-of-blob-centroid-using-opencv-cpp-python/).

<img src="https://learnopencv.com/wp-content/uploads/2018/07/single-blob-image-768x307.png" alt="Centre of Blob" width="900">


[<img src="https://learnopencv.com/wp-content/uploads/2022/07/download-button-e1657285155454.png" alt="download" width="200">](https://www.dropbox.com/scl/fo/eftkr2kxe0wrm6i386hcs/h?dl=1&rlkey=5iaq04xe7xvprktki6hvcndnx)


To run the code to find center of a single blob, run the following commands.

Python

`python3 single_blob.py --ipimage image_name`


C++

1. ``g++ single_blob.cpp `pkg-config opencv --cflags --libs` -o output``

2. `./output image_name`

To run the code to find center of multiple blobs, run the following commands:-

Python

`python3 center_of_multiple_blob.py --ipimage image_name`

C++

1. ``g++ center_of_multiple_blob.cpp `pkg-config opencv --cflags --libs` -o output``

2. `./output image_name`


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
