# SwinT_detectron2
Swin Transformer for Object Detection by detectron2

This repo contains the supported code and configuration files to reproduce object detection results of [Swin Transformer](https://arxiv.org/pdf/2103.14030.pdf). It is based on [detectron2](https://github.com/facebookresearch/detectron2).


## Results and Models

### RetinaNet

| Backbone | Pretrain | Lr Schd | box mAP | mask mAP | #params | FLOPs | config | log | model |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |:---: |
| Swin-T | ImageNet-1K | 3x | 44.6| - | - | - | [config](configs/SwinT/retinanet_swint_T_FPN_3x.yaml) | - | - |


## Usage
Please refer to [get_started.md](https://detectron2.readthedocs.io/en/latest/tutorials/getting_started.html) for installation and dataset preparation.

