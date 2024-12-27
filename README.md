<div align="center">
  <h1><strong> Image Encryption with Genetic Algorithm </strong></h1>
</div>

## Overview

This project demonstrates image encryption using a **Genetic Algorithm (GA)**. The encryption process leverages evolutionary concepts like **crossover**, **mutation**, and **tournament selection** to generate diverse encrypted images. Additionally, several image analysis methods, including **entropy**, **correlation**, and **NPCR**, are used to evaluate the encryption strength and security.

## Features

- **Genetic Algorithm for Image Encryption**:
  - Utilizes crossover, mutation, and selection to evolve encrypted images.
  - Applies XOR and weighted blending for crossover.
  - Mutation based on a defined rate to introduce randomness.
  
- **Evaluation Methods**:
  - **Entropy**: Measures the randomness of the encrypted image.
  - **Correlation**: Analyzes the similarity between the original and encrypted images.
  - **NPCR (Number of Pixels Change Rate)**: Evaluates the effectiveness of encryption by measuring pixel differences.

- **Population-based Approach**: 
  - Population is generated with random mutations and evolves over multiple generations to increase image security.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- Matplotlib

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rooshanriaz/Image-Encryption-using-Genetic-Algorithm.git
   cd image-encryption-ga
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
