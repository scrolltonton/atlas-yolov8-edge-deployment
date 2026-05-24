# YOLOv8 Edge Deployment on Huawei Atlas 200I DK A2

## Overview

This project records an end-to-end object detection deployment pipeline on Huawei Atlas 200I DK A2.

The pipeline includes dataset labeling, YOLOv8 training, ONNX export, ATC model conversion, OM model deployment, and ACL-based inference on the edge device.

## Hardware

- Huawei Atlas 200I DK A2
- Ascend 310B4

## Software and Tools

- Python
- Ultralytics YOLOv8
- ONNX
- Huawei Ascend Toolkit
- ATC
- ACL Python API
- OpenCV

## Pipeline

1. Prepare and label custom dataset
2. Train YOLOv8 model on PC
3. Export trained model to ONNX
4. Convert ONNX model to OM model using ATC
5. Deploy OM model to Huawei Atlas 200I DK A2
6. Run ACL-based inference
7. Visualize detection results

## Current Progress

- [x] Dataset labeling
- [x] YOLOv8 training
- [x] ONNX export
- [x] ATC conversion attempt
- [x] Atlas 200I DK A2 environment setup
- [ ] Clean inference script
- [ ] Add sample results
- [ ] Add complete deployment tutorial

## Notes

This repository is being organized from my previous edge AI deployment experiments. More scripts, logs, and documentation will be added gradually.

## Future Work

- Improve preprocessing and postprocessing consistency
- Add complete ACL inference code
- Add result visualization examples
- Compare PC-side and edge-side inference results
