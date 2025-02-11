# DIP-Final-Project
DIP-Final Project
# Fire and Smoke Detection using YOLOv9

This repository implements a fire and smoke detection system using the YOLOv9 model. The project involves downloading data, extracting files, loading a pre-trained YOLOv9 model, training the model, and evaluating its performance.

---

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation and Execution](#installation-and-execution)
  - [1. Install Required Packages](#1-install-required-packages)
  - [2. Download and Extract Data](#2-download-and-extract-data)
  - [3. Load the YOLOv9 Model](#3-load-the-yolov9-model)
  - [4. Train the Model](#4-train-the-model)
  - [5. Evaluate the Model](#5-evaluate-the-model)
- [Results](#results)
- [Future Work](#future-work)
- [References](#references)

---

## Introduction

This project utilizes the YOLOv9 model to detect fire and smoke in images. The main objective is to develop an efficient system for early fire detection and monitoring, which can be integrated into real-time alert systems.

---

## Features

- **Automatic Data Download**: Uses `gdown` to download a compressed dataset from Google Drive.
- **Data Extraction**: Utilizes `unrar` to extract RAR-compressed files.
- **YOLOv9 Model**: Loads a pre-trained YOLOv9 model (`yolov9m.pt`) for further training and inference.
- **Model Training**: Trains the model using a YAML configuration file that specifies data paths, class labels, and other parameters.
- **Performance Evaluation**: Generates a confusion matrix and visualizes predictions on sample images.

---

