# WaveUNet+
## train
```python
python train.py
```
## predict
```python
python predict.py
```
## Data

├── JPEGImages/           # Original image
│   ├── img1.jpg
│   ├── img2.jpg
│   └── ...
└── SegmentationClass/           # Label image
    ├── img1.png  
    ├── img2.png  
    └── ...

## requirement
torch==2.0.0+cu117
torchvision==0.15.1+cu117
opencv-python==4.11.0.86
pywavelets==1.4.1
numby==1.24.4
