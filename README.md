# Fine-Tuning Llama 2

This repository contains the notebooks and resources for fine-tuning the Llama 2 model using Parameter-Efficient Fine-Tuning (PEFT) techniques. The project leverages Google Colab's free GPU resources to optimize the model performance under limited computational capabilities.

## Project Description

The Llama 2 model developed by NousResearch is a state-of-the-art large language model known for its robust performance in natural language processing tasks. Given the high computational cost associated with training such models, this project utilizes techniques such as 4-bit quantization and Low-Rank Adaptation (LoRA) to make the training process more feasible on platforms with limited resources like Google Colab.

## Key Features

- **Efficient Fine-Tuning**: Implementing techniques like LoRA and QLoRA to reduce memory usage without compromising model performance.
- **4-bit Quantization**: Leveraging bitsandbytes library to minimize VRAM usage during training.
- **Dataset Preparation**: Utilizing a preprocessed dataset tailored for the fine-tuning process.

## Installation

Clone this repository and install the required packages:

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
pip install -r requirements.txt
