# Lane-Detection-for-Self-Driving-Cars

### This repository contains Basic Lane Detection and some pre-requisites for Advanced Lane Detection for Self-Driving Cars

- Step1 - Download the test1.mp4, chess.png, and distorted chess board.png files.
- 
- Step2 - Run the ipynb file step by step as clearly mentioned in the notebook itself.

## Techniques used in Basic Lane Detection:

- ### 1. Canny Edge Detection:
  - Read the this article on **Canny Egde Detection** https://towardsdatascience.com/canny-edge-detection-step-by-step-in-python-computer-vision-b49c3a2d8123
  - Canny edge detection is an image processing technique that extracts edges from images by detecting sudden changes in intensity. It involves several steps including smoothing with a Gaussian filter, finding gradients, non-maximum suppression, and edge tracking by hysteresis. The result is a binary image highlighting significant edges in the original image.

- ### 2. Hough Transform
  - Read this article on **Hough Transform** https://www.analyticsvidhya.com/blog/2022/06/a-complete-guide-on-hough-transform/
  - The Hough transform is a technique used in computer vision to detect geometric shapes like lines, circles, or ellipses in images. It works by representing these shapes as mathematical equations in parameter space and finding peaks in an accumulator array, indicating the presence of those shapes in the image. This method is robust to noise and partial occlusion, making it widely used in tasks like object recognition and lane detection.

  
