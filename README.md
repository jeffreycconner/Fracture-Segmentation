# Fracture-Segmentation

### Overview
Contained in this repo is the Group 5 Project of Bone Fracture Detection, where four Neural Network models were trained against the [FracAtlas](https://figshare.com/articles/dataset/The_dataset/22363012?file=43283628) dataset in an attempt to generate image segmentation networks capable of generating a bounding box surrounding the predicted fracture.

Our models are as follows:
- ResNet18 (baseline)
- DenseNet (baseline)
- Faster R-CNN (initial solution)
- YOLOv8 (refined solution)

## Steps
1. In order to run this project, first the *data_pre-processing.ipynb* notebook needs to be run. This notebook will take the data downloaded from [FracAtlas](https://figshare.com/articles/dataset/The_dataset/22363012?file=43283628) and pre-process it as needed for each of the model notebooks to use.
    - As a quike note, the attached FracAtlas folder contains the already pre-processed data, as well as any manual alterations made in the data that are not contained in the pre-processing notebook
2. After running the *data_pre-processing.ipynb* nodebook, you are now ready to run any of the model notebooks:
    - *resNet.ipynb*
    - *DenseNet.ipynb*
    - *FasterRCNN.ipynb*
    - *YOLOv8.ipynb*