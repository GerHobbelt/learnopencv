# Augmented Reality using ArUco Markers in OpenCV (C++ / Python)

**This repository contains the code for [Augmented Reality using ArUco Markers in OpenCV (C++ / Python)](https://learnopencv.com/augmented-reality-using-aruco-markers-in-opencv-c++-python/) blog post**.

[<img src="https://learnopencv.com/wp-content/uploads/2022/07/download-button-e1657285155454.png" alt="download" width="200">](https://www.dropbox.com/sh/k8mbua12pmqh4o2/AAC0N6jG7X8wtZfMUpDa9y1Ma?dl=1)

We show how to use the AruCo markers in OpenCV using an augmented reality application to replace the image inside a picture frame on a wall to display new images or videos in the frame.

### Compilation in C++

```
g++ -std=c++11 augmented_reality_with_aruco.cpp -o augmented_reality_with_aruco.out `pkg-config --cflags --libs opencv4`
```

### How to run the code

Command line usage for running the code

* Python

  * A single image:
    	
    ```
    python3 augmented_reality_with_aruco.py --image=test.jpg
    ```
    
  * A video file:

    ```
    python3 augmented_reality_with_aruco.py --video=test.mp4
    ```       

* C++:

  * A single image:
        
    ```
    ./augmented_reality_with_aruco.out --image=test.jpg
    ```

  * A video file:

    ```
     ./augmented_reality_with_aruco.out --video=test.mp4
    ```

### Results
<img src = "./augmented-reality-example.jpg" width = 1000 height = 282/>


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
