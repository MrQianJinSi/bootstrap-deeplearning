# Intro to Deep Learning for Beginners

## Prerequisites
- Math
  - Linear algebra: Matrix, Eigen Value Decomposition, SVD
  - Calculus: Derivatives of multivariable functions, Chain rule, Convexity
  - Probability theory: Bayes theorem
- Computer
  - Programming: OOP concept
  - Python: Basic Syntax
  - Linux experience(nice to have)

## Course Objectives
- Bootstrap Your Deep Learning Journey
  - 山坡上滚雪球：一旦完成开始阶段的积累，雪球就会自行滑动
  - 帮助大家入门深度学习：一旦度过摩擦力最大的启动阶段，大家就可以自行前进了
- Specific Goals
  - Fundamental Understanding: Concept and Algorithm of Deep Learning
  - Practice: Implementation in Python, especially in PyTorch

## Big Picture of Artificial Intelligence
- Artificial Intelligence
  - Rule Engine
  - Knowledge Graph
  - Machine Learning
    - SVM
    - Decision Tree
    - **Deep Learning(We ar here!)** 
    - etc
  - etc

## Deep Learning: Mathematic View
Deep Learning is a Optimization Question  
Given Input: $\mathbf{X}$, Output: $\mathbf{Y}$  
find parameter $\mathbf{\Theta}$ which minimize loss:
$$
\underset{\Theta}{\argmin}\quad L(\mathbf{Y}, f(\mathbf{X}, \mathbf{\Theta})) 
$$
## Deep Learning: Algorithm Skeleton
Algorithm Skeleton: 
1. initialize parameters
2. while not satisfy stop criteria
   1. update parameters

## Deep Learning: Parameters Number Exploding
ICP: 3+3 
SVM: ~50
AlexNet: 61M
BERT2: 340M


## lecture1
- [slides](http://introtodeeplearning.com/slides/6S191_MIT_DeepLearning_L1.pdf)

## Deep Learning: Problems
1. how to avoid overfitting(data normalization, batch normalizer, dropout)
2. how to reduce computation complexity(layer architecture, pooling, 1x1 CNN bridge)
3. how to converge more effectively (Gradient clap, Relu, Resnet)
4. how to build big dataset(ImageNet, Scannet, unsupervised learning)
5. how to accelerate training speed(Compiler Optimization, GPU, Distributing system)
6. how to reduce the difficulty of model design(Pytorch, tensorflow)
7. how to interpret the result of deep learning(visualization)