# Automated Descriptive Labels Prediction Model



## Hardware Description  
Windows personal Laptop, The computer should have the following specifications:

• Processor: 11th Gen Intel Cor i7 CPU 2.30 GHz.

• Random Access Memory: 16 GB.

• System type: 64-bit operating system.

• Windows version: Windows 10 Home, [[ note windows 11 is not compatiable ]] 

• Graphical Processing Unit (GPU): NVIDIA GeForce RTX 3060 Laptop GPU

## Requirements
- NVIDIA CUDA version 531.41
- Python version 3.10.7
- PyTorch 1.12.1+cu116
- mmcv


## Installation

```sh
git clone https://github.com/nourafd/Automated-Descriptive-Labels-Prediction-Model.git
cd mmfashion
python setup.py install
```

## Steps to run application:
1- The data is already prepared and described in [DATASET_DESCRIPTION.md](docs/DATASET_DESCRIPTION.md)

2- Run "python tools/train_predictor.py --config configs/category_attribute_predict/global_predictor_vgg.py" to train the data

3- Run "python flask/app.py" to run the application and try the demo, the result will be store in flask/result.xlsx


## REFERENCE PROJECT ==> the Automated Descriptive Labels Prediction Model was built based on mmfashion project

@inproceedings{mmfashion,
 
 title={MMFashion: An Open-Source Toolbox for Visual Fashion Analysis},
 
 author={Liu, Xin and Li, Jiancheng and Wang, Jiaqi and Liu, Ziwei},
 
 booktitle={{ACM Multimedia 2021, Open Source Software Competition},
 
 year={2021}

}


