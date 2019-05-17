# pytorch homotopy training algorithm
This is the PyTorch implementation of "An efficient homotopy training algorithm for neural networks"

## Requirements
[PyTorch](https://github.com/pytorch/pytorch)
[torchvision](https://github.com/pytorch/vision)

## Dataset
[CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)

## Run the code
To train vgg with homotopy training algorithm:
`python main_homotopy_vgg.py -a vgg13 -l 0.01 0.009 0.008 0.007 0.006 0.005 --epochs 4 -L 0.1 1`


## Accuracy
| Model            | Acc.        |  Acc. with HTA  |
| ---------------- | ----------- | ----------------|
| [VGG11]          | 91.010%     | 91.660%         | 
| [VGG13]          | 92.290%     | 93.090%         |
