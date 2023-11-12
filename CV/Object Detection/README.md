# Object Detection

**[YOLO](./YOLO-project-Rubanov.ipynb)**: a complete custom implementation 
of the SOTA one-shot detector **YOLO**. The project implements all elements 
of the model pipeline:
  * _sample processing_ for YOLO format
  * effective _data augmentations_ using the 
    [Albumentations](https://github.com/albumentations-team/albumentations/) library 
  * _architecture and loss function_ from the original
    [paper](https://arxiv.org/abs/1506.02640) 
  * _additional features_ from the paper
  * logging of metrics and model states in _Weights & Biases_
  * _visualization_ of the model's results (_bounding boxes_)
