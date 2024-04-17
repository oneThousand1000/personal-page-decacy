---
title: "iOrthoPredictor: Model-guided Deep Prediction of Teeth Alignment"
collection: publications
permalink: /publication/iothopredictor
excerpt: 'Lingchen Yang, Zefeng Shi, **Yiqian Wu**, Xiang Li, Kun Zhou, Hongbo Fu, Youyi Zheng*'
date: 2020-12-30
venue: 'ACM Transactions on Graphics (Proceedings of SIGGRAPH Asia 2020)'
paperurl: 'https://dl.acm.org/doi/10.1145/3414685.3417771'
code: 'https://github.com/Lingchen-chen/iOrthopredictor'
citation: 'http://oneThousand1000.github.io/files/bibtex/iothopredictor.html'
year: '2020'
first_author: 'no'
teaser: 'http://oneThousand1000.github.io/images/publications/iothopredictor.png'
---
![iothopredictor](http://oneThousand1000.github.io/images/publications/iothopredictor.png)



> **iOrthoPredictor: Model-guided Deep Prediction of Teeth Alignment**
>
> ACM Transactions on Graphics (Proceedings of SIGGRAPH Asia 2020)
>
> Lingchen Yang, Zefeng Shi, Yiqian Wu, Xiang Li, Kun Zhou, Hongbo Fu, Youyi Zheng*



<b>Abstract:</b>
In this paper, we present iOrthoPredictor, a novel system to visually predict teeth alignment in photographs. Our system takes a frontal face image of a patient with visible malpositioned teeth along with a corresponding 3D teeth model as input, and generates a facial image with aligned teeth, simulating a real orthodontic treatment effect. The key enabler of our method is an effective disentanglement of an explicit representation of the teeth geometry from the in-mouth appearance, where the accuracy of teeth geometry transformation is ensured by the 3D teeth model while the in-mouth appearance is modeled as a latent variable. The disentanglement enables us to achieve fine-scale geometry control over the alignment while retaining the original teeth appearance attributes and lighting conditions. The whole pipeline consists of three deep neural networks: a U-Net architecture to explicitly extract the 2D teeth silhouette maps representing the teeth geometry in the input photo, a novel multilayer perceptron (MLP) based network to predict the aligned 3D teeth model, and an encoder-decoder based generative model to synthesize the in-mouth appearance conditional on the original teeth appearance and the aligned teeth geometry. Extensive experimental results and a user study demonstrate that iOrthoPredictor is effective in qualitatively predicting teeth alignment, and applicable to the orthodontic industry. 

[![Paper](https://img.shields.io/badge/Main%20Paper-1?color=58A399&logo=data:image/svg+xml;charset=utf-8;base64,PHN2ZyB0PSIxNzEyNDkwMTQyMjM1IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjU5MTQiIHdpZHRoPSIyMDAiIGhlaWdodD0iMjAwIj48cGF0aCBkPSJNODIzLjI5NiA2MC40MTZxNjUuNTM2IDAgOTkuMzI4IDM4LjR0MzMuNzkyIDkzLjY5NnY1NDMuNzQ0cTAgMjUuNi0yMS41MDQgNDYuMDhsLTE3MS4wMDggMTYzLjg0cS0xMy4zMTIgMTEuMjY0LTIyLjUyOCAxNC4zMzZ0LTIzLjU1MiAzLjA3MkgyNTguMDQ4cS0yMy41NTIgMC00Ny4xMDQtOS43Mjh0LTQxLjk4NC0yNy42NDgtMzAuMjA4LTQzLjAwOC0xMS43NzYtNTUuODA4di02MzQuODhxMC02MC40MTYgMzMuMjgtOTYuMjU2dDk0LjcyLTM1Ljg0aDU2OC4zMnogbS0yMTUuMDQgNjQyLjA0OHExMy4zMTIgMCAyMi41MjgtOS4yMTZUNjQwIDY3MC43MnEwLTE0LjMzNi05LjIxNi0yMy4wNHQtMjIuNTI4LTguNzA0SDI4Ny43NDRxLTEzLjMxMiAwLTIyLjUyOCA4LjcwNFQyNTYgNjcwLjcycTAgMTMuMzEyIDkuMjE2IDIyLjUyOHQyMi41MjggOS4yMTZoMzIwLjUxMnogbTEyOC0xOTIuNTEycTEzLjMxMiAwIDIyLjUyOC05LjIxNlQ3NjggNDc4LjIwOHQtOS4yMTYtMjIuNTI4LTIyLjUyOC05LjIxNkgyODcuNzQ0cS0xMy4zMTIgMC0yMi41MjggOS4yMTZUMjU2IDQ3OC4yMDh0OS4yMTYgMjIuNTI4IDIyLjUyOCA5LjIxNmg0NDguNTEyeiBtNjMuNDg4LTE5MS40ODhxMTMuMzEyIDAgMjIuNTI4LTkuMjE2dDkuMjE2LTIzLjU1MnEwLTEzLjMxMi05LjIxNi0yMi41Mjh0LTIyLjUyOC05LjIxNmgtNTEycS0xMy4zMTIgMC0yMi41MjggOS4yMTZUMjU2IDI4NS42OTZxMCAxNC4zMzYgOS4yMTYgMjMuNTUydDIyLjUyOCA5LjIxNmg1MTJ6IiBwLWlkPSI1OTE1IiBmaWxsPSIjZmZmZmZmIj48L3BhdGg+PC9zdmc+)](https://dl.acm.org/doi/10.1145/3414685.3417771)
[![Github](https://img.shields.io/github/stars/Lingchen-chen/iOrthopredictor)](https://github.com/Lingchen-chen/iOrthopredictor)

Recommended citation: 

```
@article{10.1145/3414685.3417771,
author = {Yang, Lingchen and Shi, Zefeng and Wu, Yiqian and Li, Xiang and Zhou, Kun and Fu, Hongbo and Zheng, Youyi},
title = {iOrthoPredictor: model-guided deep prediction of teeth alignment},
year = {2020},
publisher = {Association for Computing Machinery},
volume = {39},
number = {6},
issn = {0730-0301},
journal = {ACM Trans. Graph.},
articleno = {216},
numpages = {15},
}
```