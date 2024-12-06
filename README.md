# Sign-Language-Detection-Project-Yolov5
We are using this Dataset from Roboflow. [Dataset](https://universe.roboflow.com/sign-m1fzu/sign-language-0qewx/dataset/2)

### 1. Create environment

```bash
conda create -p sign python=3.8 -y

```

### Label Img tool:

1. https://github.com/heartexlabs/labelImg

2. [exe](https://github.com/entbappy/Sign-Language-Generation-From-Video-using-YOLOV5/raw/master/Annotation%20Tool/labelImg.exe)

[G-Drive](https://drive.google.com/drive/folders/18AIDI4pOAcYC-zSCPpYvRxWaydjOqS1W?usp=sharing)


### Yolov5

https://github.com/ultralytics/yolov5


## Installation of yolov5 locally

```bash
pip install -r yolov5/requirements.txt
```

## run the final :
```bash
python detect.py --weights best.pt --img 416 --conf 0.5 --source 0
```