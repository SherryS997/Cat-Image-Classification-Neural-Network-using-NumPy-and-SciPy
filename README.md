# Cat Image Classification Neural Network

This project implements a neural network using numpy and scipy to classify cat images from non-cat images. The neural network is built and trained in a Jupyter Notebook. The dataset used for training and testing consists of cat and non-cat images.

## Overview

The neural network architecture comprises several layers, including linear, ReLU (Rectified Linear Unit), and sigmoid activation functions. It is implemented as a 4-layer neural network with customizable layer dimensions.

## Project Structure

- `cat_image_classification.ipynb`: Jupyter Notebook containing the code for the neural network implementation, training, and evaluation.
- `datasets/`: Directory containing the dataset for training and testing (`train_catvnoncat.h5` and `test_catvnoncat.h5`).

## Dependencies

The project relies on the following libraries:

- NumPy
- SciPy
- h5py
- Matplotlib
- PIL (Python Imaging Library)

## Usage

1. **Dataset Preparation**: Ensure the dataset (`train_catvnoncat.h5` and `test_catvnoncat.h5`) is placed in the `datasets/` directory.
2. **Jupyter Notebook Execution**: Open and execute the `cat_image_classification.ipynb` Jupyter Notebook to train and evaluate the neural network.
3. **Modify Parameters (Optional)**: Modify the neural network architecture, learning rate, or number of iterations in the notebook for experimentation.

## Results

The trained neural network achieves a certain level of accuracy in classifying cat images from non-cat images. The notebook provides visualizations of the training process, accuracy, and misclassified images.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the [MIT License](LICENSE).