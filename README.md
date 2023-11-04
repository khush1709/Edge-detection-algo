# Image Edge Detection with OpenCV

This repository contains Python code for performing edge detection on images using OpenCV, specifically implementing the Canny and Marr-Hildreth (LoG filter) edge detection techniques. It also demonstrates how to enhance the edges in the original image by adding the detected edges back to it.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Prerequisites

Before using this code, ensure you have the following prerequisites installed on your system:

- Python 3
- OpenCV (`opencv-python`)
- NumPy
- Matplotlib

You can install the required packages using the following command:
```shell
pip install opencv-python numpy matplotlib
```

## Installation
1) Clone the repository to your local machine:
    ```shell
    git clone https://github.com/khush1709/Edge-detection-algo.git
   ```
    
2) Change the current directory to the project folder:
   ```shell
   cd edge-detection
   ```
   
## Usage
1) Place the image you want to process in the project folder and name it img.jpg.
2) Run the Python script to perform edge detection and display the results:
   ```shell
   python edge_detection.py
   ```
The script will generate and display the original image, Canny edge detection result, Marr-Hildreth edge detection result, and the enhanced output images for both methods.

## Results
The results of the edge detection techniques, along with the enhanced images, will be displayed using Matplotlib. You can see the following images:

1) Original Image
2) Generated Canny Edge Detection
3) Output Image (Canny)
4) Generated Marr-Hildreth Edge Detection
5) Output Image (Marr-Hildreth)

## Contributing
If you'd like to contribute to this project, feel free to open issues, create pull requests, or suggest improvements. We welcome your contributions!
