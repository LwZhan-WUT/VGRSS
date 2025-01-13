# VGRSS: Datasets and Models for Visual Grounding in Remote Sensing Ship Images
---
**Author**:Yaxiong Chen, Liwen Zhan, Yichen Zhao, Shengwu Xiong, Xiaoqiang Lu

This is the official dataset and source code for the paper "VGRSS: Datasets and Models for Visual Grounding in Remote Sensing Ship Images".  

If you find this project helpful, please give it a STAR ⭐!

## 📢 News  
- [2025/01/12]：Release the RSSVG and SARVG datasets.

## 🔍 Download Dataset  
You can download our constructed RSSVG and SARVG datasets from the following link:  
[https://drive.google.com/drive/folders/1wAGJAn5yIUIvBuK5rUNfo-CKDiKq1A57?usp=sharing]  

The directory and file structure are as follows:

```
./                          # current (project) directory
├── data_loader.py          # Load data
├── main.py                 # Main code for training, validation, and test
├── README.md
└── RSSVG/                  # RSSVG dataset
    ├── Annotations/        # Query expressions and bounding boxes
    │   ├── 00001.xml/
    │   └── ..some xml files..
    ├── JPEGImages/         # Remote sensing images
    │   ├── 00001.jpg/
    │   └── ..some jpg files..
    ├── ImageSets/         
    │   ├── train.txt           # ID of training set
    │   ├── val.txt             # ID of validation set
    │   └── test.txt            # ID of test set
└── SARVG/                  # SARVG dataset
    ├── Annotations/        # Query expressions and bounding boxes
    │   ├── 00001.xml/
    │   └── ..some xml files..
    ├── JPEGImages/         # Remote sensing images
    │   ├── 00001.jpg/
    │   └── ..some jpg files..
    ├── ImageSets/         
    │   ├── train.txt           # ID of training set
    │   ├── val.txt             # ID of validation set
    │   └── test.txt            # ID of test set
```

## 📜 Reference  
If you find this code useful, please cite our paper. Fork and Star to stay updated with future releases.

```bibtex

```

## 🙏 Acknowledgments  
The RSSVG dataset is derived from the ship sections of the FAIR1M, CGWX, and DIOR-RSVG datasets, while the SARVG dataset is sourced from the SAR-Ship-Dataset. We express our gratitude to the authors of these datasets for making their data available, which greatly facilitated our research. Part of our code is based on TransVG, and we extend our thanks to the respective authors for their valuable contributions. We also thank the School of Computer and Artificial Intelligence, Wuhan University of Technology, for supporting this research.
