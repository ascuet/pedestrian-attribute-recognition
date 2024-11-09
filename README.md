# A Transfer Learning Approach to Recognize Pedestrian Attributes 

## Abstract
Pedestrian attribute recognition (PAR) has recently created a significant impact because of its soft bio-metric property to recognize individuals. The popularity of the pedestrian attribute recognition task is gained after deep learning, especially the convolutional neural network. This paper represents a transfer learning approach for the pedestrian attributes recognition task because of its high performance and low training cost. The Mask RCNN object detector extracts the images of isolated pedestrians. After that, the preprocessed images are passed to different CNN architectures, i.e., Inception ResNet v2, Xception, ResNet 101 v2, to extract the spatial features. Experiments reveal that the Xception architecture outperforms the competition with a 90.33% accuracy rate. Following that, some experiments on the Xception architecture are carried out by freezing the last 4, 8, 12, 16, 20, all, and none layers (excluding the fully connected layers). For the RAP v2 dataset, experimental results show that freezing the last 16 layers provides the best accuracy, 92.52%, outperforming existing methods in terms of accuracy.

## Keywords
Pedestrian attribute recognition (PAR), Pedestrain attributes, Pedestrian Retrieval, Attribute-based Person Retrieval, Modality Fusion,  Video Surveillance Scenarios, Transfer Learning, RCNN

## Citation
If you find this paper helpful in your work, you can cite using the following bibtex:
```bibtex
@incollection{sakib2023transfer,
  title={A Transfer Learning Approach to Recognize Pedestrian Attributes},
  author={Sakib, Saadman and Sen, Anik and Deb, Kaushik},
  booktitle={Applied Intelligence for Industry 4.0},
  pages={145--161},
  year={2023},
  publisher={Chapman and Hall/CRC}
}
```

## Dataset
Richly Annotated Pedestrian (RAP) dataset v2.0 is used in this paper. The dataset was proposed in the paper titled **"A Richly Annotated Pedestrian Dataset for Person Retrieval in Real Surveillance Scenarios"**. The samples were collected from uncontrolled multi-camera surveillance scenarios. RAP dataset v2.0 is an extended version of RAP dataset v1.0. In total, RAP dataset v2.0 has 84,928 attribute annotated pedestrian samples, and 26,638 of them are also identity annotated. If you use RAP dataset v2.0 in your work, you can cite the following paper:
```bibtex
@article{li2018richly,
  title={A richly annotated pedestrian dataset for person retrieval in real surveillance scenarios},
  author={Li, Dangwei and Zhang, Zhang and Chen, Xiaotang and Huang, Kaiqi},
  journal={IEEE transactions on image processing},
  volume={28},
  number={4},
  pages={1575--1590},
  year={2018},
  publisher={IEEE}
}
```
