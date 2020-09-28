![](1.png?raw=true "RSAN")
# Residual Spatial Attention Network for Retinal Vessel Segmentation
This code is for the paper: Residual Spatial Attention Network for Retinal Vessel Segmentation. We report state-of-the-art performances on DRIVE and CHASE DB1 datasets.

Code written by Changlu Guo, Budapest University of Technology and Economics(BME).


We train and evaluate on Ubuntu 16.04, it will also work for Windows and OS.

## Quick start 

Train:
Run train_drive.py or train_chase.py

Test:
Run eval_drive.py or eval_chase.py


## Environments
Keras 2.3.1  <br>
Tensorflow==1.14.0 <br>


## If you are inspired by our work, please cite this paper.

#### Structured dropout convolutional block
@INPROCEEDINGS{8942005,  <br>
author={C. {Guo} and M. {Szemenyei} and Y. {Pei} and Y. {Yi} and W. {Zhou}}, <br> 
booktitle={2019 IEEE 19th International Conference on Bioinformatics and Bioengineering (BIBE)},   <br>
title={SD-Unet: A Structured Dropout U-Net for Retinal Vessel Segmentation},   <br>
year={2019},  <br>
volume={},  <br>
number={},  <br>
pages={439-444},}<br>

@misc{guo2020residual, <br>
    title={Residual Spatial Attention Network for Retinal Vessel Segmentation}, <br>
    author={Changlu Guo and Márton Szemenyei and Yugen Yi and Wei Zhou and Haodong Bian}, <br>
    year={2020}, <br>
    eprint={2009.08829}, <br>
    archivePrefix={arXiv}, <br>
    primaryClass={eess.IV} <br>
}

