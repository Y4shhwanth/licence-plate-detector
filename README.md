# License Plate Recognition using PaddleOCR

This script performs license plate recognition on a recorded video using PaddleOCR. It detects license plates in each frame of the video, draws bounding boxes around them, and displays the processed video with the recognized text.

## Prerequisites

- [PaddlePaddle](https://github.com/PaddlePaddle/Paddle) (installed via pip)
- [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) (installed via pip)
- [OpenCV](https://github.com/opencv/opencv)
- Google Colab environment (if running in Colab)

## Installation

Install the required dependencies using pip:

```bash
%pip install paddlepaddle
%pip install paddleocr
```

## Usage
Set up your Google Colab environment or Python environment with the required dependencies.
Record a video containing scenes with license plates that you want to recognize.
Replace video_path variable with the path to your recorded video.
Run the script. It will process the video, perform license plate recognition, and save the output video with bounding boxes and recognized text.

## Output
The processed video will be saved as output_video.mp4 in the current directory.
