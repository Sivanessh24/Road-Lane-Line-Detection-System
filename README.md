# Road-Lane-Line-Detection-System
TASK-1 of AI-ML Internship

This project implements a lane detection system using computer vision techniques and deep learning.


- [Introduction](#introduction)
- [Features](#features)
- [Code](#code)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)

# Lane Detection System

This project implements a lane detection system using computer vision techniques and deep learning.

## Introduction

The Lane Detection System aims to enhance road safety by accurately detecting lane markings on the road and providing real-time feedback to drivers. 
This system uses advanced computer vision and deep learning techniques to process video feeds from a vehicle's camera and identify lane lines.

## Features

- Real-time lane line detection
- Supports video feed processing
- Uses Canny edge detection and Hough transform for line detection
- Averaging of detected lines for stability
- Easy to configure and extend

## Code


### Files Description

- **main.py**: This script contains the core functionality of the application. It handles [describe what main.py does in your project].

- **gui.py**: This script implements the graphical user interface (GUI) for the application. It provides [describe the purpose and features of gui.py].

### Installation

To run these scripts, ensure you have Python installed on your system.

### Usage

To run the application:

1. **Run `main.py`**:

    ```bash
    python main.py
    ```

2. **Run `gui.py`**:

    ```bash
    python gui.py
    ```

### Prerequisites

- Python 3.6 or later
- OpenCV
- NumPy

### Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/SunhithReddy647/lane-detection-system.git
    cd lane-detection-system
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Place your video file (`test_video.mp4`) in the project directory.
2. Run the lane detection script:
    ```sh
    python lane_detection.py                            
    ```
3. Press `q` to quit the video window.

## Configuration

The `lane_detection.py` script can be configured by modifying parameters such as:

- Canny edge detection thresholds
- Region of interest vertices
- Hough transform parameters

Modify these parameters in the script to suit your needs.

## Contributing

We welcome contributions to improve this project. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a pull request.


## Contact

For questions or suggestions, please contact:

T.Sunhith Reddy
linkedin:- www.linkedin.com/in/sunhith-reddy-t



