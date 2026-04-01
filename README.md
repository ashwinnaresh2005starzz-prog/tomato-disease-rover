# Tomato Disease Rover

A deep learning–based tomato leaf disease classification project designed for real-time agricultural monitoring on a mobile robotic platform.

## Overview

Tomato crops are highly vulnerable to multiple leaf diseases that can reduce yield and affect crop quality if not identified early. Manual disease inspection is time-consuming, depends heavily on expert knowledge, and becomes difficult to scale across larger farms. This project addresses that challenge through an image-based disease classification system built using convolutional neural networks and organized for deployment on a rover-based smart agriculture platform.

This repository presents a professional portfolio version of the project. It brings together the model training workflow, result visualizations, disease sample assets, rover prototype documentation, and the final paper into a clean and well-structured GitHub repository.

## Project Objective

The main objective of this project is to develop a practical tomato leaf disease detection pipeline that can support real-time agricultural monitoring. The work focuses on classifying tomato leaf diseases from images using lightweight deep learning architectures, with an emphasis on balancing high accuracy and deployment suitability for edge-oriented systems.

## Key Highlights

- Multi-class tomato leaf disease classification
- Comparison of lightweight CNN architectures
- EfficientNet-based training workflow
- Training and validation performance visualization
- Field-oriented rover prototype documentation
- Telegram output sample for result delivery
- Clean repository structure for portfolio and future development
- Final paper included in the `docs` folder

## Repository Structure

```text
tomato-disease-rover-GitHub/
├── assets/
│   ├── diagrams/
│   ├── images/
│   ├── outputs/
│   └── plots/
├── data/
│   ├── processed/
│   ├── raw/
│   └── samples/
├── docs/
│   └── paper.pdf
├── notebooks/
│   ├── evaluation/
│   └── training/
├── paper/
├── src/
│   ├── inference/
│   ├── models/
│   ├── training/
│   └── utils/
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt