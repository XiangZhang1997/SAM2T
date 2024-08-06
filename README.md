# SAM2T
The official implementation of SAM2T

python /home/s1/ZX/job/Vessel/train.py -dp "/home/s1/ZX/job/Vessel/datasets/DRIVE" --val 

python /home/s1/ZX/job/Vessel/test.py -dp "/home/s1/ZX/job/Vessel/datasets/DRIVE" -wp "/home/s1/ZX/job/Vessel/pretrained_weights/DRIVE/SAM2T/checkpoint-epoch20.pth" --show

python /home/s1/ZX/job/Vessel/FR_UNet/c_metrics.py -dp "/home/s1/ZX/job/Vessel/datasets/DRIVE"

