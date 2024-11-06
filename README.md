# AdaptiDAN
Security Capstone Lab Package

**README.md**

# AdaptiDAN: A Genetic Algorithm Approach to Jailbreak Language Models

## Overview
AdaptiDAN is a novel framework designed to generate jailbreak prompts for language models using Genetic Algorithms (GA). It builds on the limitations of existing approaches like AutoDAN, employing evolutionary strategies to adapt and rephrase restricted prompts in order to bypass the safety mechanisms of language models. This repository contains the code for implementing the AdaptiDAN algorithm, including the comparative analysis with AutoDAN.

## Features
- **Genetic Algorithm Implementation**: Leverages evolutionary strategies such as selection, crossover, and mutation.
- **Prompt Diversification**: Generates multiple variations of prompts to effectively bypass restrictions.
- **Controlled Mutations**: Ensures ethical framing of prompts by limiting disruptive changes.
- **Quantitative and Qualitative Evaluation**: Compares AdaptiDAN's performance with AutoDAN.

## Getting Started

### Prerequisites
To run the notebook, you will need the following software and libraries:
- Python 3.7+
- Jupyter Notebook or Google Colab
- Git (optional, for cloning the repository)

### Installation
1. Clone the repository using Git:
    ```bash
    git clone https://github.com/asvika-07/AdaptiDAN.git
    ```
2. Navigate to the project directory:
    ```bash
    cd AdaptiDAN
    ```
3. Install the required Python packages using `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```
4. Alternatively, you can run the notebook directly in Google Colab by uploading it.

### Usage
- **Notebook**: Open `AdaptiDAN.ipynb` in Jupyter Notebook or Google Colab.
- **Run the Cells**: The notebook is divided into different sections, including data generation, genetic algorithm operations, and comparative analysis.
- **Modify Prompts**: You can modify the initial restricted prompts to observe how AdaptiDAN adapts and evolves new prompts.

### Project Structure
- `AdaptiDAN.ipynb`: Main notebook containing the implementation of AdaptiDAN.
- `requirements.txt`: List of dependencies required to run the notebook.
- `README.md`: Documentation on how to use the project.

### Example
To generate a bypass prompt for a restricted phrase, modify the prompt in the notebook and run the cells. The Genetic Algorithm will evolve and optimize the prompts over generations to achieve a successful bypass.

## Results
AdaptiDAN has shown a 45% success rate in bypassing language model restrictions in our experiments, compared to a 23% success rate for AutoDAN. This improvement is attributed to the adaptability of the genetic algorithm used.

## Tools and Technologies Used
- **Programming Language**: Python
- **Libraries**: DEAP, transformers, PyTorch
- **Platforms**: Google Colab, Jupyter Notebook



---



