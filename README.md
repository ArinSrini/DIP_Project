High-Quality Image Restoration Following Human Instructions

This project presents InstructIR, a novel approach to image restoration that uses human-written instructions to guide the restoration process. InstructIR can recover high-quality images from their degraded counterparts, considering multiple degradation types such as denoising, deraining, deblurring, dehazing, and (low-light) image enhancement.

Introduction

Image restoration is a fundamental problem in computer vision that aims to recover a clean image from a degraded observation. Traditional methods often require specific knowledge about the type of degradation, which can be limiting. All-in-one restoration models address this issue by using degradation-specific information as prompts to guide the restoration process. However, these models still lack the flexibility to handle diverse and nuanced human instructions.

InstructIR

InstructIR overcomes this limitation by using a natural language processing (NLP) module to understand human-written instructions. The NLP module extracts key information from the instructions, such as the desired level of detail, noise reduction, and color enhancement. This information is then used to guide the image restoration process.

Key Features

Human-guided restoration: InstructIR allows users to provide specific instructions for how they want the image to be restored.
Multi-task restoration: InstructIR can handle a variety of image degradation tasks, including denoising, deraining, deblurring, dehazing, and (low-light) image enhancement.
State-of-the-art results: InstructIR achieves state-of-the-art results on several restoration benchmarks.
Getting Started

This repository includes the following:

demo.ipynb: A Jupyter notebook that demonstrates how to use InstructIR.
models: Pre-trained InstructIR models for different restoration tasks.
datasets: Datasets used to train and evaluate InstructIR.
code: Source code for the InstructIR model and NLP module.
To get started, please refer to the demo.ipynb notebook.

Citation

If you use InstructIR in your research, please cite the following paper:

@misc{conde2024instructir,
  title={High-Quality Image Restoration Following Human Instructions},
  author={Marcos V. Conde, Gregor Geigle, Radu Timofte},
  year={2024},
  journal={arXiv preprint},
}
I hope this helps!
