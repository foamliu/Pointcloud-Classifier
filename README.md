# Pointcloud Classifier

Pointcloud classification based on kaolin's implementation of PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation.

## Dataset

[ModelNet10](https://modelnet.cs.princeton.edu/) contains CAD models from the 10 categories

![image](https://github.com/foamliu/Pointcloud-Classifier/raw/master/images/shape_samples.jpg)

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

### Result

<pre>
Train loss: 0.11194922991405921
Train accuracy: 0.9599359069879239
100%|████████| 15/15 [00:08<00:00,  1.70it/s]
Val loss: 0.09645371088020814
Val accuracy: 0.9600000063578288
</pre>