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

- Step 1: download basic emotions dataset of [RAF-DB](http://www.whdeng.cn/raf/model1.html), and make sure it have the structure like following:
 
```
./RAF-DB/
         train/
               0/
                 train_09748.jpg
                 ...
                 train_12271.jpg
               1/
               ...
               6/
         test/
              0/
              ...
              6/

[Note] 0: Neutral; 1: Happiness; 2: Sadness; 3: Surprise; 4: Fear; 5: Disgust; 6: Anger
```

- Step 2: download pre-trained model from
   [Google Drive](https://drive.google.com/file/d/1tro_RCovLKNACt4MKYp3dmIvvxiOC2pi/view?usp=sharing),
    and put it into ***./checkpoint***.
    
- Step 3: change the ***project_path*** and ***data_path***  to your path in *main.py*

- Step 4: run ```python main.py ```
