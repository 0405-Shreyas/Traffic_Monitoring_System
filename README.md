# Computer Vision Project

This repository contains a computer vision project focused on vehicle detection and counting.

## Overview

- **Detection.py**: This script captures video frames and uses the Viola-Jones algorithm to detect cars in the video. It utilizes a trained XML classifier (`haarcascade_cars.xml`) to identify cars and draws rectangles around detected vehicles.

- **Count.py**: This script captures video frames and computes the difference between consecutive frames to detect motion. It then identifies contours and calculates centroids to count the number of vehicles passing through a defined line.

- **Unfiltered Images**: This folder contains images without any filters applied.

- **Background_Subtracted_Images**: Contains images that have undergone background subtraction to highlight the vehicles.

- **computer_vision_report.pdf**: A detailed report on the computer vision techniques and methodologies used in this project.

## Dependencies

- OpenCV: Used for video processing and computer vision tasks.

## Usage

1. Ensure you have the required dependencies installed.
2. Run the `Detection.py` script to detect vehicles in a video.
3. Run the `Count.py` script to count the number of vehicles passing through a defined line in a video.

## Results

The results of the vehicle detection can be viewed in the `Background_Subtracted_Images` and `Unfiltered_Images` folders.

## Future Work

- Improve the accuracy of vehicle detection in varying lighting conditions.
- Implement real-time vehicle tracking and speed estimation.

## License

[MIT License](LICENSE)
