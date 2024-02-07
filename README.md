# InstructIR: High-Quality Image Restoration Following Human Instructions

Welcome to our project repository! We are Arindham Srinivasan (21BCE1262) and Arvind Venkat Ramanan (21BCE1160), and we are thrilled to present our collaborative project on high-quality image restoration following human instructions.

## Project Overview

In this project, we introduce an innovative approach to image restoration called InstructIR. Our model leverages human-written instructions to guide the restoration process, resulting in high-quality images from their degraded versions. We have developed a comprehensive solution that addresses various degradation types, including denoising, deraining, deblurring, dehazing, and low-light image enhancement.

## Repository Contents

- `demo_images.ipynb`: This notebook contains a demonstration of InstructIR using sample images. It provides step-by-step instructions on how to use the model and showcases its capabilities with demo images.
  
- `custom_images.ipynb`: Here, we provide a tutorial on using InstructIR with custom images. You can follow along to apply the model to your own images and observe the restoration results.

## Project Details

### High-Quality Image Restoration Following Human Instructions

This project presents InstructIR, a novel approach to image restoration that uses human-written instructions to guide the restoration process. InstructIR can recover high-quality images from their degraded counterparts, considering multiple degradation types such as denoising, deraining, deblurring, dehazing, and (low-light) image enhancement.

### Introduction

Image restoration is a fundamental problem in computer vision that aims to recover a clean image from a degraded observation. Traditional methods often require specific knowledge about the type of degradation, which can be limiting. All-in-one restoration models address this issue by using degradation-specific information as prompts to guide the restoration process. However, these models still lack the flexibility to handle diverse and nuanced human instructions.

### InstructIR

InstructIR overcomes this limitation by using a natural language processing (NLP) module to understand human-written instructions. The NLP module extracts key information from the instructions, such as the desired level of detail, noise reduction, and color enhancement. This information is then used to guide the image restoration process.

### Key Features

- **Human-guided restoration:** InstructIR allows users to provide specific instructions for how they want the image to be restored.
- **Multi-task restoration:** InstructIR can handle a variety of image degradation tasks, including denoising, deraining, deblurring, dehazing, and (low-light) image enhancement.
- **State-of-the-art results:** InstructIR achieves state-of-the-art results on several restoration benchmarks.

### Getting Started

This repository includes the following:

- `demo.ipynb`: A Jupyter notebook that demonstrates how to use InstructIR.
- `models`: Pre-trained InstructIR models for different restoration tasks.
- `datasets`: Datasets used to train and evaluate InstructIR.
- `code`: Source code for the InstructIR model and NLP module.

To get started, please refer to the `demo.ipynb` notebook.

### Citation

If you use InstructIR in your research, please cite the following paper:

`@misc{conde2024instructir,
  title={High-Quality Image Restoration Following Human Instructions},
  author={Marcos V. Conde and Gregor Geigle and Radu Timofte},
  year={2024},
  journal={arXiv preprint},
}`

[![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/abs/2401.16468)
[![Paper page](https://huggingface.co/datasets/huggingface/badges/resolve/main/paper-page-sm.svg)](https://huggingface.co/papers/2401.16468)

