# AFANet

  Implemention of Paper：Deep Adaptive Feature Aggregation in Multi-task Convolutional Neural Networks
  
## Requirements  

  Python >= 3.6  
  numpy  
  PyTorch >= 1.0  
  torchvision >= 0.2   
  tensorboardX  
  
## Installation
  1. Clone the repo:
  ```
  git clone https://github.com/IJCAI2020-MTL/AFANet.git   
  cd AFANet
  ```
  2. For custom dependencies:
  ```
  pip install matplotlib tensorboardX   
  ```

## For Training
  1. Configure your dataset path in `Dataloader.py`.   
  2. Deeplabv3+ networks with ResNet backbone are used to train semantic segmentation and depth prediction(see full input arguments in ```train_multi.py``` ):
  ```
  python train_multi.py
  ```


