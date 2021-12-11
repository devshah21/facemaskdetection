# facemaskdetection
Using YOLO (You Only Look Once), an object detection algorithm to detect face masks. 

## Annotating Images

I used Kaggle to download a dataset. After downloading this dataset, I used a graphical image annotating tool to label the images. The annotations should be saved as xml files. 

### Installation

For MacOs:
```
pip3 install pyqt5 lxml 
make qt5py3
python3 labelImg.py
python3 labelImg.py [IMAGE_PATH] [PRE-DEFINED CLASS FILE]
```

![Annotation](https://drive.google.com/uc?export=view&id=1ZuSzF5W_w0_pUrvH1JQurtUse1FSSYNK)
