# Fine Tuning and Deployment for Text Summarization

This repository contains the code for fine-tuning and deploying a text summarization model. The project leverages state-of-the-art transformer models to generate concise summaries from longer texts.



## Introduction

The Fine Tuning and Deployment for Text Summarization project aims to provide an end-to-end solution for text summarization. It involves fine-tuning a pre-trained transformer model on a specific dataset and deploying the model for real-time summarization tasks.



## Architecture

The architecture of the project includes the following components:

1. **Pre-trained Model**: Utilizes a transformer model such as BERT and pegasus from the Hugging Face library.
2. **Fine-Tuning Pipeline**: Fine-tunes the model on a specific summarization dataset.
3. **Deployment Interface**: Uses FastAPI to create a web interface for the summarization service.
4. **Evaluation Metrics**: Implements metrics like ROUGE to evaluate the performance of the summarization model.

## Installation

To install and set up the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/SarathMohanIITD/Fine_tuning_and_Deployment_for_Text_Summerization.git
    cd Fine_tuning_and_Deployment_for_Text_Summerization
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```





