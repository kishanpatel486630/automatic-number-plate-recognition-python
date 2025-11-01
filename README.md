# automatic-number-plate-recognition-python-yolov8

Automatic Number Plate Recognition (ANPR) system using YOLOv8 in Python. Detects and extracts vehicle license plates from images or video streams with high accuracy. Includes real-time detection, OCR-based text extraction, and easy integration for traffic monitoring or security applications.

<p align="center">
<!-- <a href="https://www.youtube.com/watch?v=fyJB1t0o0ms"> -->
    <!-- <img width="600" src="https://utils-computervisiondeveloper.s3.amazonaws.com/thumbnails/with_play_button/anpr_yolo2.jpg" alt="Watch the video"> -->
    <!-- </br>Watch on YouTube: Automatic number plate recognition with Python, Yolov8 and EasyOCR ! -->
</a>
</p>

## data

The video I used in this tutorial can be downloaded [here](https://www.pexels.com/video/traffic-flow-in-the-highway-2103099/).

## models

A Yolov8 pretrained model was used to detect vehicles.

A license plate detector was used to detect license plates. The model was trained with Yolov8 using [this dataset](https://universe.roboflow.com/roboflow-universe-projects/license-plate-recognition-rxg4e/dataset/4) and following this [step by step tutorial on how to train an object detector with Yolov8 on your custom data](https://github.com/computervisioneng/train-yolov8-custom-dataset-step-by-step-guide).

The trained model is available in my [Patreon](https://www.patreon.com/ComputerVisionEngineer).

## dependencies

The `sort` module needs to be downloaded from [this repository](https://github.com/abewley/sort) as mentioned in the [video](https://youtu.be/fyJB1t0o0ms?t=1120).

## notes

This repository contains a working demo that:

- detects vehicles with a YOLOv8 model,
- detects license plates with a separate detector,
- extracts plate numbers with OCR and writes results to CSV,
- visualizes results in `out.mp4` using `visualize.py`.

Feel free to open an issue if you need help running the demo or training your own detector.
