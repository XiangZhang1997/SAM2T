# SAM2T
![](https://img.shields.io/badge/license-MIT-blue)
The official implementation of SAM2T
# SAM2T Project

## Overview
SAM2T is a project for vessel segmentation using deep learning techniques. This repository contains scripts for training, testing, and evaluating models on the DRIVE dataset.

## Scripts

### `train.py`
This script is used for training the model on the DRIVE dataset.

**Usage:**
1. Prepare your dataset in the appropriate format.
2. Configure the training parameters in the script or via command-line arguments.
3. Run the script using the following command:
    ```bash
    python train.py --config path/to/config.yaml
    ```

### `test.py`
This script is used for evaluating the trained model on test images.

**Usage:**
1. Ensure that you have a trained model available.
2. Configure the testing parameters in the script or via command-line arguments.
3. Run the script using the following command:
    ```bash
    python test.py --model path/to/trained_model.pth --test_data path/to/test_data
    ```

### `metrics.py`
This script calculates various evaluation metrics for the segmentation results.

**Usage:**
1. Ensure that the segmentation results and ground truth maps are available.
2. Run the script to calculate metrics using the following command:
    ```bash
    python metrics.py --predictions path/to/predictions --ground_truth path/to/ground_truth
    ```

## Example
1. **Training**: Prepare your dataset, then run training:
    ```bash
    python train.py --config path/to/config.yaml
    ```
2. **Testing**: Evaluate your trained model:
    ```bash
    python test.py --model path/to/trained_model.pth --test_data path/to/test_data
    ```
3. **Metrics**: Calculate performance metrics:
    ```bash
    python metrics.py --predictions path/to/predictions --ground_truth path/to/ground_truth
    ```

## Requirements
- Python 3.x
- PyTorch
- numpy
- other dependencies as specified in `requirements.txt`

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
