# Human Detection using OpenCV HOG Descriptor

This Python script uses OpenCV's HOG (Histogram of Oriented Gradients) descriptor to detect humans in images or videos. It provides functionality to detect humans, display bounding boxes around them, and optionally save the processed output.

## Prerequisites

- Python 3.x
- OpenCV (`pip install opencv-python`)
- imutils (`pip install imutils`)

## Usage

### Setup
1. **Clone the repository**:
git clone https://github.com/shrutidip/Human-Detection-and-Counting.git
cd Human-Detection-and-Counting


2. **Install dependencies**:

### Running the Script

You can use the script to detect humans in images or videos and optionally save the processed output.

#### Command Line Arguments

- `-v` or `--video`: Path to the video file for human detection.
- `-i` or `--image`: Path to the image file for human detection.
- `-o` or `--output`: (Optional) Path to save the output video or image with detected humans.

#### Examples

1. **Detect humans in a video**:

2. **Detect humans in an image and save the output**:

### Interacting with the Script

- Upon running the script with a video or image path, it will display the output with bounding boxes around detected humans.
- Press `q` to quit the video playback (if applicable) or close the image window.

Steps to Use:
1.Setup: Clone the repository and navigate into it.
2.Dependencies: Install Python dependencies (opencv-python and imutils).
3.Running the Script: Use command line arguments (-v, -i, -o) to specify input video or image paths and optionally save the output.

