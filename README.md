# RandWireNN(Randomly Wired Neural Network)

PyTorch implementation of :
[Exploring Randomly Wired Neural Networks for Image Recognition](https://arxiv.org/abs/1904.01569).

## Update
- 2019/4/7: The code of RandWireNN are released.

## Requirements
- python packages
  - pytorch>=0.4.0
  - torchvision>=0.2.1
  - tensorboardX
  - pyyaml
  - [CVdevKit](https://github.com/JiaminRen/CVdevKit.git)
  - networkx
  
## Data Preparation
Download the ImageNet dataset and put them into the `{repo_root}/data/imagenet`.

## Training a model from scratch
```
./train.sh configs/config_regular_c109_n32.yaml
```
## License
All materials in this repository are released under the  Apache License 2.0.
