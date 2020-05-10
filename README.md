# ECE 523: ML-Project : Generating and Analyzing Devanagari Digits using Generative Adversatial Network
## Author 1: Srishti Gupta
## Author 2: I-Chun Lien

This repository contains data, code and results for the ECE 523: Engineering Applications to Machine Learning and Data Analytics project. The distribution of different contents in this repository is as follows:

## 1. Train_Test Dataset
The folder contains Devanagari Hindi digits used in the project. Theu were downloaded from https://www.kaggle.com/ashokpant/devanagari-character-dataset/version/1

## 2. GAN.ipynb
This folder containd the code for the project

## 3. Results
This folder contains results ontained from changing various hyper-parameters. 
1) Activation functions: Discriminator: sigmoid, Generator: sigmoid, Optimizer in Discriminator: Dropout: 0.4, Convulutional Kernel: 4x4
2) Activation functions: Discriminator: sigmoid, Generator: sigmoid, Optimizer in Discriminator: Dropout: 0.4, Convulutional Kernel: 2x2
3) Activation functions: Discriminator: sigmoid, Generator: sigmoid, Optimizer in Discriminator: Dropout: 0.2, Convulutional Kernel: 4x4
4) Activation functions: Discriminator: sigmoid, Generator: sigmoid, Optimizer in Discriminator: Dropout: 0.2, Convulutional Kernel: 2x2
5) Activation functions: Discriminator: sigmoid Generator: ReLU, Optimizer in Discriminator: Dropout: 0.2
6) Activation functions: Discriminator: sigmoid Generator: tanh, Optimizer in Discriminator: Dropout: 0.2
7) Activation functions: Discriminator: ReLU Generator: sigmoid, Optimizer in Discriminator: Dropout: 0.2
8) Activation functions: Discriminator: tanh Generator: tanh, Optimizer in Discriminator: Dropout: 0.2

## 4. ECE 523 Final project.pdf
This folder contains the project report along with loss graph functions.
