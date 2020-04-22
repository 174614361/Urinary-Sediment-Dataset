# Urinary Sediment Dataset
a dataset consisting of 5,376 annotated images corresponding to 7 categories of urinary sediment particle

- cast
- cryst (crystals)
- epith (epithelial cell)
- epithn (epithelial nuclei)
- eryth (erythrocyte) 
- leuko (leukocyte)
- mycete

# Format
The dataset is in the [PASCAL VOC](https://pjreddie.com/projects/pascal-voc-dataset-mirror/) format.



```sh
/VOCdevkit
└── Urinary Sediment Dataset
    ├── Annotations
    ├── ImageSets
    │   └── Main
    │       ├── test.txt
    │       ├── train.txt
    │       └── val.txt
    └── JPEGImages
```

- train set: 4256 images
- val set: 852 images
- test set: 268 images


# Downloading Dataset
https://drive.google.com/drive/folders/18VqmoqK7dVSdxiyEE6qCfIpS8UOqqIBS?usp=sharing

# Citing Dataset
If you find Dataset useful in your research, please consider citing:

    @article{liang2018object,
      title={Object detection based on deep learning for urine sediment examination},
      author={Liang, Yixiong and Tang, Zhihong and Yan, Meng and Liu, Jianfeng},
      journal={Biocybernetics and Biomedical Engineering},
      volume={38},
      number={3},
      pages={661--670},
      year={2018},
      publisher={Elsevier}
    }

    @article{liang2018end,
      title={An End-to-End System for Automatic Urinary Particle Recognition with Convolutional Neural Network},
      author={Liang, Yixiong and Kang, Rui and Lian, Chunyan and Mao, Yuan},
      journal={Journal of medical systems},
      volume={42},
      number={9},
      pages={165},
      year={2018},
      publisher={Springer}
    }

    @INPROCEEDINGS{9054367, 
      author={M. {Yan} and Q. {Liu} and Z. {Yin} and D. {Wang} and Y. {Liang}}, 
      booktitle={ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, 
      title={A Bidirectional Context Propagation Network for Urine Sediment Particle Detection in Microscopic Images}, 
      year={2020}, 
      volume={}, 
      number={}, 
      pages={981-985}
    }
