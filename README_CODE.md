# Code for Transfer Learning-Based Poultry Disease Classification

This folder contains a PyTorch training script (`train_transfer_learning.py`) that expects an ImageFolder-structured dataset:
- train/
  - class1/
  - class2/
- val/
  - class1/
  - class2/

Example usage:
```bash
python train_transfer_learning.py --data_dir /path/to/data --output_dir ./output --epochs 10 --batch_size 32
```
