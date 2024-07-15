# Stable Diffusion from Scratch

This project implements Stable Diffusion from scratch, based on the original architecture and concepts. It aims to provide a deeper understanding of the inner workings of Stable Diffusion by building it step-by-step.

## Important Note on Model Weights and Tokenizer

Due to file size limitations, the necessary model weights and tokenizer files are not included in this repository. You will need to download these files separately and place them in the `data` folder before running the project.

### Download Required Files

1. Tokenizer files:
   - Download `vocab.json` and `merges.txt` from [HuggingFace Stable Diffusion v1-5 Tokenizer](https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main/tokenizer)
   - Save both files in the `data` folder of this project

2. Model weights:
   - Download `v1-5-pruned-emaonly.ckpt` from [HuggingFace Stable Diffusion v1-5](https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main)
   - Save the file in the `data` folder of this project

Ensure these files are in place before attempting to run the project.

## Project Overview

This implementation of Stable Diffusion includes:

- Custom UNET architecture
- Attention mechanisms
- Diffusion process
- CLIP text encoder integration
- Image generation pipeline

## Key Features

- Modular architecture allowing for easy experimentation
- Step-by-step implementation of the diffusion process
- Integration with pre-trained CLIP model for text encoding
- Custom sampling methods for image generation

## Getting Started

### Prerequisites

- Python 3.8+
- PyTorch 2.0+
- transformers library
- PIL (Python Imaging Library)

### Installation

1. Clone this repository: