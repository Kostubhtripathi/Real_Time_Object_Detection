
# Real-Time Object Detection

This repository contains a Jupyter Notebook for real-time object detection using a pre-trained TensorFlow model. 
The project demonstrates the use of OpenCV for video/image processing and Matplotlib for visualization.

## Features

- Load and configure a pre-trained TensorFlow SSD model (MobileNet V3).
- Perform object detection on images or video streams.
- Visualize detection results with bounding boxes.

## Prerequisites

- Python 3.6 or higher
- TensorFlow model files:
  - `ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt` (configuration file)
  - `frozen_inference_graph.pb` (pre-trained model file)

Ensure these files are downloaded and available in the specified paths before running the notebook.

## Installation

1. Clone this repository.
2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter Notebook:

   ```bash
   jupyter notebook RealTimeObject.ipynb
   ```

## Usage

1. Update the paths for the TensorFlow model files in the notebook.
2. Run the notebook cells sequentially to load the model, process input data, and visualize results.

## Dependencies

See `requirements.txt` for the list of dependencies.

## Acknowledgments

- TensorFlow Object Detection API
- OpenCV for image/video processing
