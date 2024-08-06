# SAM2T
![](https://img.shields.io/badge/license-MIT-blue)
The official implementation of SAM2T

## Usage

### 1. Train the Model

To train the model on the DRIVE dataset, run the following command:

```bash
python /home/s1/ZX/job/Vessel/train.py -dp "/home/s1/ZX/job/Vessel/datasets/DRIVE" --val

### 2. Test the Model

To test the model on the DRIVE dataset, run the following command:

```bash
python /home/s1/ZX/job/Vessel/test.py -dp "/home/s1/ZX/job/Vessel/datasets/DRIVE" -wp "/home/s1/ZX/job/Vessel/pretrained_weights/DRIVE/SAM2T/checkpoint-epoch20.pth" --show

### 3. Evaluate the Model

To evaluate the model on the DRIVE dataset, run the following command:

```bash
python /home/s1/ZX/job/Vessel/FR_UNet/c_metrics.py -dp "/home/s1/ZX/job/Vessel/datasets/DRIVE"

