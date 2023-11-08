# Wagon-Number-Detection

## Project Overview
The Wagon Number Detection project automates the identification of train wagon numbers from video footage. Utilizing cutting-edge image processing and machine learning techniques, this system was developed during a project-based internship at Vizag Steel Plant. The core functionality revolves around the detection and recognition of numerical sequences on train wagons, which is crucial for logistics and inventory management in industrial settings.

## Key Features
- Automated detection of wagon numbers in video streams.
- Integration of image processing algorithms for accurate number localization.
- Application of machine learning for robust digit recognition.
- Developed and tested in an industrial environment for practical applicability.

## Installation Requirements
- Python 3.x
- OpenCV library
- Pre-trained machine learning model for text detection (e.g., EAST text detector).

## Setup and Execution
1. Ensure you have Python and OpenCV installed on your system.
2. Download the pre-trained EAST text detector model and place it in the project directory.
3. Run the text_detection1.py script to start the wagon number detection process on your video file.

## Usage
To run the project, execute the following command in your terminal:
```
python text_detection1.py --video path_to_your_video --east frozen_east_text_detection.pb
```
Replace `path_to_your_video` with the actual path to your video file and `frozen_east_text_detection.pb` with the path to the downloaded EAST model file.

## Contributions
This project is open for contributions and improvements. Please feel free to fork the repository, make changes, and submit a pull request.
