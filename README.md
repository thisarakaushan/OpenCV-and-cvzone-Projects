# OpenCV and cvzone Projects

This repository contains a Python project that demonstrates various functionalities of OpenCV and the cvzone library. The 
project covers image manipulation, video processing, shape drawing, text overlay, basic image processing techniques, and hand 
tracking using cvzone.

## Table of Contents
* Getting Started
  - Prerequisites
  - Installation

* Usage
  - Resizing and Displaying Images
  - Reading Images and Videos
  - Drawing Shapes and Text
  - Image Processing Functions
  - Hand Tracking

* Contributing

### Getting Started

1. Prerequisites
   
  * Python 3.x
  * OpenCV
  * cvzone library (You can install it using pip install cvzone)
    
2. Installation
Clone the repository:
```
git clone https://github.com/thisarakaushan/opencv-cvzone-project.git
cd opencv-cvzone-project
```

3. Install the required dependencies:
```
pip install opencv-python numpy cvzone
```

### Usage

1. Resizing and Displaying Images
   
The project showcases how to load and resize images using OpenCV.

2. Reading Images and Videos
   
In this section, you're reading images and video streams from a webcam and displaying them using OpenCV. You've also added a loop to continuously display video frames until the user presses quit.

3. Drawing Shapes and Text
   
This part covers drawing shapes (rectangle, circle, line) and text on images using OpenCV. It also shows how to create a blank image using NumPy.

4. Image Processing Functions
   
Here, you're applying various image processing functions to the loaded image using OpenCV.

Converting the image to grayscale Applying Gaussian blur Detecting edges using the Canny edge detector Dilating the image Eroding the image

5. Hand Tracking

In this section, you're using the HandTrackingModule from the cvzone library to detect and track hands from a webcam feed.

Set up the hand detector with specified parameters. The code within the loop reads frames from the webcam, detects hands, and retrieves information about the detected hands (landmark points, bounding box, hand type, etc.). It also detects the number of fingers raised by each hand. The detected information is then displayed on the video frame.

### Contributing

Contributions are welcome! If you find any issues or want to enhance the project, feel free to open a pull request.
