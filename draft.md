# Intro to Deep Learning for Beginners

## Concept: Loss Function
how to evlaute loss function
computation complexity
converge speed
more steep for right value

## Basic Blocks FCN

## First Network: MLP

## Why MLP Works
universal approximate theroy

## Recall: Matrix Calculus

## Alogorithm: Optimaztion Framework
From Mathmatica view, Deep Learning is Optimaztion Problem.

stop critea => loss function  
update paramters  => 

## Algorithm: loss function
optimazer target

## Algorithm: Optimizaer

## Algorithm: Procedure
Back Propagation
how to train

## Practice: Basic Pytorch Syntax
Matrix Operations

## Back Propagation: house pricing problem
interactive example
writting code and push to github


## quiz:
the difference between DL and normal optimaztion problem

too big: from 30 to million  upto x10^6

alexnet: 61M para
BERT2:340M para

question:
1. how to avoid overfitting(data normalization, batch normalizer, dropout)
2. how to reduce computation complexity(layer architecture, pooling, 1x1 CNN bridge)
3. how to converge more effectively (Gradient clap, Relu, Resnet)
4. how to get the dataset(ImageNet, Scannet, unsupervised learning)
5. how to accelerate training speed(Compiler Optimazation, GPU, Distributing system)
6. how to accelerate model design(Pytorch, tensorflow)

## Back Propagation for FCN


## Assignment
MLP for mnist
code template?


## limitation of MLP

- computation 
- gradient vanishing
  - explained by SVD
- gradient exploding

## Basic Blocks CNN
https://github.com/vdumoulin/conv_arithmetic/blob/master/README.md
A guide to convolution arithmetic for deep learning


## Back Propagation for FCN

## First CNN Network: AlexNet

## Why CNN Works?
Visualization 
https://dudeperf3ct.github.io/visualize/cnn/catsvsdogs/2018/12/02/Power-of-Visualizing-Convolution-Neural-Networks/#why-does-regularization-work?
https://distill.pub/

## limititation of CNN

## Basic Blocks RNN

## RNN example

## Concept:Computation Graph
Why framework can handle new network?

## Ultimate Abstraction: DAG 
model of every network

## Framework Underhood:
implementate DAG

while loop






## Engneer tricks
1. data argumentation
2. pretrain
3. adaptive learning rate
4. drop out
5. max/avg pooling



# Topic: Object Detection

ref: RCNN / FastRCNN /Faster RCNN / YOLO

How to Understand Big Networks?
from output to input

# Topic: Image Segmentation



## Deep Learning: Problems
1. how to avoid overfitting(data normalization, batch normalizer, dropout)
2. how to reduce computation complexity(layer architecture, pooling, 1x1 CNN bridge)
3. how to converge more effectively (Gradient clap, Relu, Resnet)
4. how to build big dataset(ImageNet, Scannet, unsupervised learning)
5. how to accelerate training speed(Compiler Optimization, GPU, Distributing system)
6. how to reduce the difficulty of model design(Pytorch, tensorflow)
7. how to interpret the result of deep learning(visualization)

ref:
- [Feature Pyramid Networks for Object Detection](https://arxiv.org/pdf/1612.03144.pdf) 变尺度的图像特征提取
- [Network In Network](https://arxiv.org/pdf/1312.4400.pdf) 贡献了1x1 CNN的想法
- [Going deeper with convolutions(GoogLeNet)](https://arxiv.org/pdf/1409.4842.pdf) 第一次把CNN网络推进到20+层
- [You Only Look Once: Unified, Real-Time Object Detection](https://arxiv.org/pdf/1506.02640.pdf)  one stage 目标检测算法
- 
- 