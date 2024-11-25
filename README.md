# Multi-stream Information Complementarity Network for RGB-D Camouflaged Object Detection (MIC-Net)
## 1. Required libraries
python = 3.11.5
conda = 23.7.4
pytorch = 2.1.0
numpy = 1.24.3
torchvision = 0.16.0

## 2. Usage
Please follow the tips to download the datasets and pre-trained model:

Download RGB-D COD dataset from [https://pan.baidu.com/s/1MAh94WmBYl9HQaXG7orrVg?pwd=htrb 提取码：htrb]

Download RGB-D SOD dataset from [https://pan.baidu.com/s/12QntwlRaEc6ulcNXAhyVMg?pwd=ze4y 提取码：ze4y]

Download pretrained backbone weights from [https://pan.baidu.com/s/1tbCtY6AVWSBLguqS6UAAhA?pwd=lwgm 提取码：lwgm]

Training command :python train.py

Testing command :python test.py

Results:
Qualitative results: we provide the prediction maps of RGB-D COD task, you can download them from 
[https://pan.baidu.com/s/1BFte3pw7YUkyHTUWaVtj7A?pwd=x3r4 提取码：x3r4]

Qualitative results: we provide the prediction maps of RGB-D SOD task, you can download them from 
[https://pan.baidu.com/s/1v2txi-1S84pUkfyC8VDE0A?pwd=sx3p 提取码：sx3p]

evaluation :python eval.py
