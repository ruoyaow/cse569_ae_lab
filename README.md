# Adversarial Examples Lab

## Overview
This lab introduces you to adversarial examples in machine learning - inputs specifically designed to cause AI models to make mistakes. You'll learn and try how to generate these examples. Detailed per-step instructions are provided in ```AE_lab.ipynb```.

## Environment Setup

### Installation

We're using conda as our virtual environment management system to ensure consistent dependencies across different systems.

1. **Install Miniconda**: 
   - If you don't have conda installed, follow the [Miniconda installation instructions](https://www.anaconda.com/docs/getting-started/miniconda/install#quickstart-install-instructions) for your operating system.
   - Verify installation by running `conda --version` in your terminal.

2. **Create and activate the environment**:
   ```bash
   # Create a new conda environment named 'ae_lab' with Python 3.10
   conda create -n ae_lab python=3.10 -y
   
   # Activate the environment
   conda activate ae_lab
   
   # Install required packages
   pip install -r requirements.txt
   ```

## Running the Lab

1. **Start Jupyter Lab**:
   ```bash
   jupyter lab
   ```
   This will open Jupyter Lab in your default web browser.

2. **Navigate to the notebook**:
   - Open `AE_lab.ipynb` from the file browser.
   - Follow the instructions in the notebook.
   
## Acknowledgement

[Paper](https://arxiv.org/abs/1412.6572)

[PyTorch Tutorial](https://pytorch.org/tutorials/beginner/fgsm_tutorial.html)

