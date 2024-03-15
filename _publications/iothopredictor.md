---
title: "iOrthoPredictor: Model-guided Deep Prediction of Teeth Alignment"
collection: publications
permalink: /publication/iothopredictor
excerpt: 'Lingchen Yang, Zefeng Shi, **Yiqian Wu**, Xiang Li, Kun Zhou, Hongbo Fu, Youyi Zheng.'
date: 2020-12-30
venue: 'ACM Transactions on Graphics (Proc. of Siggraph Asia 2020), 39(6), Article 216.'
paperurl: 'https://dl.acm.org/doi/10.1145/3414685.3417771'
citation: 'http://oneThousand1000.github.io/files/bibtex/iothopredictor.html'
year: '2020'
first_author: 'no'
teaser: 'http://oneThousand1000.github.io/images/publications/iothopredictor.png'
---
![iothopredictor](http://oneThousand1000.github.io/images/publications/iothopredictor.png)

<b>Abstract:</b>
In this paper, we present iOrthoPredictor, a novel system to visually predict teeth alignment in photographs. Our system takes a frontal face image of a patient with visible malpositioned teeth along with a corresponding 3D teeth model as input, and generates a facial image with aligned teeth, simulating a real orthodontic treatment effect. The key enabler of our method is an effective disentanglement of an explicit representation of the teeth geometry from the in-mouth appearance, where the accuracy of teeth geometry transformation is ensured by the 3D teeth model while the in-mouth appearance is modeled as a latent variable. The disentanglement enables us to achieve fine-scale geometry control over the alignment while retaining the original teeth appearance attributes and lighting conditions. The whole pipeline consists of three deep neural networks: a U-Net architecture to explicitly extract the 2D teeth silhouette maps representing the teeth geometry in the input photo, a novel multilayer perceptron (MLP) based network to predict the aligned 3D teeth model, and an encoder-decoder based generative model to synthesize the in-mouth appearance conditional on the original teeth appearance and the aligned teeth geometry. Extensive experimental results and a user study demonstrate that iOrthoPredictor is effective in qualitatively predicting teeth alignment, and applicable to the orthodontic industry. 




[[pdf]](https://dl.acm.org/doi/10.1145/3414685.3417771)

Recommended citation: [[bibtex]](http://oneThousand1000.github.io/files/bibtex/iothopredictor.html)