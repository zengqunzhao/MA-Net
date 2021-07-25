# MA-Net

*Zengqun Zhao, Qingshan Liu, Shanmin Wang. "[Learning Deep Global Multi-scale and Local Attention Features 
for Facial Expression Recognition in the Wild](https://doi.org/10.1109/TIP.2021.3093397)". IEEE Transactions on Image Processing.*

## Requirements
- Python >= 3.6
- PyTorch >= 1.2
- torchvision >= 0.4.0

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
    
- Step 3: change ***data_path*** in *main.py* to your path 

- Step 4: run ```python main.py ```

## Citation

```
@article{zhao2021learning,
  title={Learning Deep Global Multi-scale and Local Attention Features for Facial Expression Recognition in the Wild},
  author={Zhao, Zengqun and Liu, Qingshan and Wang, Shanmin},
  journal={IEEE Transactions on Image Processing},
  volume={30},
  pages={6544-6556},
  year={2021},
  publisher={IEEE}
}
```

## Note
The samples' number of CAER-S dataset employed in our work should be: all (69,982 samples), training set (48,995 samples), and test set (20,987 samples). We apologize for the typos in our paper.
