# Pointcloud Classifier

Pointcloud classification based on kaolin's implementation of PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation.

## Dataset

[ModelNet10](https://modelnet.cs.princeton.edu/) contains CAD models from the 10 categories

![image](https://github.com/foamliu/Pointcloud_Classifier/raw/master/images/shape_samples.jpg)

## Dependencies
- Python 3.6.8
- PyTorch 1.3.0

## Usage

### Data preprocess
Extract CAD models:
```bash
$ python extract.py
```

## Dependencies
- Python 3.6.8
- PyTorch 1.3.0
- Kaolin 0.1.0

## Usage

### Train
```bash
$ python train.py
```

To visualize the training process：
```bash
$ tensorboard --logdir=runs
```

