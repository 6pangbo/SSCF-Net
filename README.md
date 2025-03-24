## Self-Supervised Learning Driven Cross-Domain Feature Fusion Network for Hyperspectral Image Classification
This is a code demo for the paper "Self-Supervised Learning Driven Cross-Domain Feature Fusion Network for Hyperspectral Image Classification" 

## Datasets
You can download the hyperspectral datasets in mat format at: http://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes, and move the files to `./datasets` folder.

An example dataset folder has the following structure:
```
datasets
├── IP
│   ├── Indian_pines_corrected.mat
│   ├── Indian_pines_gt.mat
└── Salinas
│   ├── salinas_corrected.mat
│   ├── salinas_gt.mat

```
## Usage:
Take SSCF-Net method : 
1. Download the required data set and move to folder`./datasets`.
2. To run the file, you need to download the VGG pre-training weights file (vgg16_bn-6c64b313.pth).
   The VGG pre-training weight file can be downloadfrom the following link:
   Link: https://pan.baidu.com/s/1iOYOaiWXibaaIpapb_GFsQ
   Extract code：0tdu
3. Taking 5 labeled samples per class as an example, run `test_SA.py`
