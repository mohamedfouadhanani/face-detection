# Face Detection with YOLOv5 <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->

- [Introduction](#introduction)
- [Sections](#sections)
  - [Dependency Acquisition](#dependency-acquisition)
    - [Dependency Installation](#dependency-installation)
    - [Dependency Import](#dependency-import)
  - [Dataset Collection](#dataset-collection)
    - [Image Capture](#image-capture)
    - [Image Labelling](#image-labelling)
  - [Model Re-training](#model-re-training)
  - [Inference](#inference)

## Introduction

In this project, I implemented a face detection algorithm with [Ultralytics' YOLOv5](https://github.com/ultralytics/yolov5) using the deep learning framework **PyTorch**, for further explanations checkout the jupyter notebook.

## Sections

The following are the steps completed in order the make this project happen.

### Dependency Acquisition

#### Dependency Installation

This section in the notebook covers the explanation and the commands to install the dependencies of the project.

#### Dependency Import

This section in the notebook covers the code to import the dependencies of the project to the jupyter notebook.

### Dataset Collection

#### Image Capture

This section in the notebook covers the explanation and the code to capture images from a webcam using [opencv](https://github.com/opencv/opencv).

#### Image Labelling

This section in the notebook covers image labelling with the tool [labelImg](https://github.com/heartexlabs/labelImg).

### Model Re-training

This section in the notebook covers the command ran in order to re-train the pretrained YOLOv5s model with the collected and labelled dataset in previous sections.

### Inference

This section in the notebooks covers different ways of making use of the new model for inference.
