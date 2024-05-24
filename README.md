# AI4EO-Project

This project demonstrates image classification using Artificial Neural Networks (ANN), Convolutional Neural Networks (CNN), and Vision Transformers (ViT). It showcases the complete workflow from data loading and model training to result visualization.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model Description](#model-description)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project implements image classification using various neural network architectures: ANN, CNN, and ViT. It covers data augmentation, model training, and evaluation, and ultimately displays the performance and prediction results of the different models.

## Installation

Clone the repository or download the notebook


## Usage

1. Ensure your dataset is organized in the following structure:
    ```
    data/
    ├── category1/
    │   ├── image1.jpg
    │   ├── image2.jpg
    │   └── ...
    ├── category2/
    │   ├── image1.jpg
    │   ├── image2.jpg
    │   └── ...
    └── ...
    ```

2. Run the Jupyter Notebook to perform model training and evaluation:
    ```bash
    jupyter notebook Project.ipynb
    ```

## Project Structure

- `Project.ipynb`: Main notebook file containing complete code for data loading, model building, training, and evaluation.
- `data/`: Dataset folder containing images organized by category.

## Model Description

This project uses three different neural network models for image classification:

1. **Artificial Neural Network (ANN)**:
    - A basic neural network model suitable for simple image classification tasks.

2. **Convolutional Neural Network (CNN)**:
    - A model that extracts spatial features from images, suitable for handling image data.

3. **Vision Transformer (ViT)**:
    - A transformer-based model that can effectively handle global information in images.

## Results

The training process will output various charts, including training loss and accuracy, confusion matrix, and sample prediction results. For example:

- **Training Loss and Accuracy:**

  ![Loss and Accuracy](path/to/loss_accuracy_plot.png)

- **Confusion Matrix:**

  ![Confusion Matrix](path/to/confusion_matrix.png)

- **Sample Predictions:**

  ![Sample Predictions](path/to/sample_predictions.png)

## Contributing

We welcome contributions! If you have any suggestions for improvements or find any issues, please submit a PR or issue.

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
