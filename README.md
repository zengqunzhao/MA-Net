# MA-Net

PyTorch implement of our paper *“Learning Deep Global Multi-scale and Local Attention Features 
for Facial Expression Recognition in the Wild”*, This work is under submission.

## Requirements
- Python 3.6
- PyTorch 1.2
- torchvision 0.4.0
- numpy
- matplotlib
- datetime
- shutil
- time
- argparse
- os

## Training

- Step 1: prepare [RAF-DB](www.whdeng.cn/raf/model1.html) dataset.

- Step 2: download pre-trained model from
   [Google Drive](https://drive.google.com/file/d/1tro_RCovLKNACt4MKYp3dmIvvxiOC2pi/view?usp=sharing),
    and put it into ***./checkpoint***.
    
- Step 3: change the ***project_path*** and ***data_path***  to your path in *main.py*

- Step 4: run ```python main.py ```
