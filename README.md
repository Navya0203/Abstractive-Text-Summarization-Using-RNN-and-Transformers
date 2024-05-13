# Abstractive-Text-Summarization-Using-RNN-and-Transformers


This repository contains implementations of abstractive text summarization using Recurrent Neural Networks (RNN) with Gated Recurrent Units (GRU),Recurrent Neural Networks with Reinforcement learning and Transformer architectures. The project aims to explore and compare how different neural network models perform in generating concise and coherent summaries from extensive text data.

## Repository Structure

- **Custom_Transformer_Model.ipynb**: Jupyter notebook with a custom Transformer model tailored for text summarization.
- **RNN_Model.ipynb**: Demonstrates abstractive text summarization using a GRU-based RNN.
- **T5_implementation.ipynb**: Application of the pre-trained T5 model to the text summarization task.
- **README.md**: Provides an overview and instructions for setting up and running the models.

## Models Overview

1. **RNN Model**
   - Uses GRUs to sequentially process text data and generate summaries, focusing on capturing temporal text dependencies.

2. **Transformer Model**
   - Implements self-attention mechanisms to assess the importance of each word in the text, aiming to capture complex word relationships more effectively than RNNs.

3. **T5 Model**
   - Utilizes a pre-trained Transformer model fine-tuned for summarization, benefiting from transfer learning to enhance summary quality efficiently.

## Setup and Usage

1. Clone the repository:
   ```bash
   git clone <repository-url>
