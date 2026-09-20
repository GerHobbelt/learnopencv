# CNN based Image Colorization using OpenCV
This repository contains code for the blog post [Convolutional Neural Network, CNN based Image Colorization using OpenCV](https://learnopencv.com/convolutional-neural-network-based-image-colorization-using-opencv/).

<img src="https://learnopencv.com/wp-content/uploads/2018/07/colorization-example-1024x414.png" alt="CNN based Image Colorization" width="900">

[<img src="https://learnopencv.com/wp-content/uploads/2022/07/download-button-e1657285155454.png" alt="download" width="200">](https://www.dropbox.com/scl/fo/oy70bb6ntgikapcczq487/h?dl=1&rlkey=suwfba3j7c52u37aqq7dfvw7i)

## Usage

The small support files (`pts_in_hull.npy` and `models/colorization_deploy_v2.prototxt`) are now stored directly in this repo. Run `getModels.sh` only to download the large `colorization_release_v2.caffemodel` from the repository release assets.

Attribution for the vendored support files and the mirrored model asset is documented in [ASSET_ATTRIBUTION.md](./ASSET_ATTRIBUTION.md).

	sudo chmod a+x getModels.sh
	./getModels.sh

Python:
Commandline usage to colorize 
a single image:
	python3 colorizeImage.py --input greyscaleImage.png
a video file:
	python3 colorizeVideo.py --input greyscaleVideo.mp4


C++:

## Compilation examples
g++ `pkg-config --cflags --libs opencv4` colorizeImage.cpp -o colorizeImage.out -lopencv_core -lopencv_dnn -lopencv_highgui -lopencv_imgcodecs -lopencv_imgproc -std=c++11 
g++ `pkg-config --cflags --libs opencv4` colorizeVideo.cpp -o colorizeVideo.out -lopencv_core -lopencv_dnn -lopencv_highgui -lopencv_imgcodecs -lopencv_imgproc -lopencv_videoio -std=c++11 


## Commandline usage to colorize 
a single image:
	./colorizeImage.out greyscaleImage.png
a video file:
	./colorizeVideo.out greyscaleVideo.mp4


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
