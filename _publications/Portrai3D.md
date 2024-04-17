---
title: "Portrait3D: Text-Guided High-Quality 3D Portrait Generation Using Pyramid Representation and GANs Prior"
collection: publications
permalink: /publication/Portrait3D
excerpt: '**Yiqian Wu**, [Hao Xu](https://xh38.github.io/), [Xiangjun Tang](https://yuyujunjun.github.io/), [Xien Chen](https://github.com/xienchenn), [Siyu Tang](https://inf.ethz.ch/people/person-detail.MjYyNzgw.TGlzdC8zMDQsLTg3NDc3NjI0MQ==.html), Zhebin Zhang, Chen Li, [Xiaogang Jin*](http://www.cad.zju.edu.cn/home/jin)'
date: 2024-03-24
venue: "preprint"
paperurl: 'https://arxiv.org/abs/2404.10394'
citation: 'http://oneThousand1000.github.io/files/bibtex/portrait3d.html'
supplementary_materials: 'https://drive.google.com/file/d/1LasG-urCA7rEoITHofBwEk0CloXM0DwX/view?usp=sharing'
year: '2024'
first_author: 'yes'
teaser: 'http://oneThousand1000.github.io/images/publications/portrait3d.png'
---
![portrait3d](http://oneThousand1000.github.io/images/publications/portrait3d.png)

<b>Abstract:</b>

Existing neural rendering-based text-to-3D-portrait generation methods typically make use of human geometry prior and diffusion models to obtain guidance. However, relying solely on geometry information introduces issues such as the Janus problem, over-saturation, and over-smoothing.
We present Portrait3D, a novel neural rendering-based framework with a novel joint geometry-appearance prior to achieve text-to-3D-portrait generation that overcomes the aforementioned issues. To accomplish this, we train a 3D portrait generator, 3DPortraitGAN-Pyramid, as a robust prior. This generator is capable of producing 360° canonical 3D portraits, serving as a starting point for the subsequent diffusion-based generation process. To mitigate the "grid-like" artifact caused by the high-frequency information in the feature-map-based 3D representation commonly used by most 3D-aware GANs, we integrate a novel pyramid tri-grid 3D representation into 3DPortraitGAN-Pyramid. To generate 3D portraits from text, we first project a randomly generated image aligned with the given prompt into the pre-trained 3DPortraitGAN-Pyramid's latent space. The resulting latent code is then used to synthesize a pyramid tri-grid. Beginning with the obtained pyramid tri-grid, we use score distillation sampling to distill the diffusion model's knowledge into the pyramid tri-grid. Following that, we utilize the diffusion model to refine the rendered images of the 3D portrait and then use these refined images as training data to further optimize the pyramid tri-grid, effectively eliminating issues with unrealistic color and unnatural artifacts.
Our experimental results show that Portrait3D can produce realistic, high-quality, and canonical 3D portraits that align with the prompt.

[![Paper](https://img.shields.io/badge/Main%20Paper-1?color=58A399&logo=data:image/svg+xml;charset=utf-8;base64,PHN2ZyB0PSIxNzEyNDkwMTQyMjM1IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjU5MTQiIHdpZHRoPSIyMDAiIGhlaWdodD0iMjAwIj48cGF0aCBkPSJNODIzLjI5NiA2MC40MTZxNjUuNTM2IDAgOTkuMzI4IDM4LjR0MzMuNzkyIDkzLjY5NnY1NDMuNzQ0cTAgMjUuNi0yMS41MDQgNDYuMDhsLTE3MS4wMDggMTYzLjg0cS0xMy4zMTIgMTEuMjY0LTIyLjUyOCAxNC4zMzZ0LTIzLjU1MiAzLjA3MkgyNTguMDQ4cS0yMy41NTIgMC00Ny4xMDQtOS43Mjh0LTQxLjk4NC0yNy42NDgtMzAuMjA4LTQzLjAwOC0xMS43NzYtNTUuODA4di02MzQuODhxMC02MC40MTYgMzMuMjgtOTYuMjU2dDk0LjcyLTM1Ljg0aDU2OC4zMnogbS0yMTUuMDQgNjQyLjA0OHExMy4zMTIgMCAyMi41MjgtOS4yMTZUNjQwIDY3MC43MnEwLTE0LjMzNi05LjIxNi0yMy4wNHQtMjIuNTI4LTguNzA0SDI4Ny43NDRxLTEzLjMxMiAwLTIyLjUyOCA4LjcwNFQyNTYgNjcwLjcycTAgMTMuMzEyIDkuMjE2IDIyLjUyOHQyMi41MjggOS4yMTZoMzIwLjUxMnogbTEyOC0xOTIuNTEycTEzLjMxMiAwIDIyLjUyOC05LjIxNlQ3NjggNDc4LjIwOHQtOS4yMTYtMjIuNTI4LTIyLjUyOC05LjIxNkgyODcuNzQ0cS0xMy4zMTIgMC0yMi41MjggOS4yMTZUMjU2IDQ3OC4yMDh0OS4yMTYgMjIuNTI4IDIyLjUyOCA5LjIxNmg0NDguNTEyeiBtNjMuNDg4LTE5MS40ODhxMTMuMzEyIDAgMjIuNTI4LTkuMjE2dDkuMjE2LTIzLjU1MnEwLTEzLjMxMi05LjIxNi0yMi41Mjh0LTIyLjUyOC05LjIxNmgtNTEycS0xMy4zMTIgMC0yMi41MjggOS4yMTZUMjU2IDI4NS42OTZxMCAxNC4zMzYgOS4yMTYgMjMuNTUydDIyLjUyOCA5LjIxNmg1MTJ6IiBwLWlkPSI1OTE1IiBmaWxsPSIjZmZmZmZmIj48L3BhdGg+PC9zdmc+)](https://arxiv.org/abs/2404.10394)
[![Suppl](https://img.shields.io/badge/Supplementary-1?color=378CE7&logo=data:image/svg+xml;charset=utf-8;base64,PHN2ZyB0PSIxNzEyNDkwMTgyMzc1IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9Ijg5MDIiIHdpZHRoPSIyMDAiIGhlaWdodD0iMjAwIj48cGF0aCBkPSJNNDg2LjQgNDA5LjZIMjgyLjE4NTE0M2E0MS4zOTg4NTcgNDEuMzk4ODU3IDAgMCAwLTQxLjc2NDU3MiA0MC45NmMwIDIyLjY3NDI4NiAxOC43MjQ1NzEgNDAuOTYgNDEuNzY0NTcyIDQwLjk2aDk2LjMyOTE0M2EzNjIuNzg4NTcxIDM2Mi43ODg1NzEgMCAwIDAtOTYuMzI5MTQzIDI0NS43NmMwIDk0LjU3MzcxNCAzNi42NDQ1NzEgMTgwLjUxNjU3MSA5Ni4zMjkxNDMgMjQ1Ljc2SDE1Ni43NDUxNDNBODIuNzk3NzE0IDgyLjc5NzcxNCAwIDAgMSA3My4xNDI4NTcgOTAxLjEyVjgxLjkyQzczLjE0Mjg1NyAzNi42NDQ1NzEgMTEwLjU5MiAwIDE1Ni43NDUxNDMgMGg2NjguNzQ1MTQzYzQ2LjA4IDAgODMuNjAyMjg2IDM2LjY0NDU3MSA4My42MDIyODUgODEuOTJ2MzgxLjE0NzQyOWEzODAuMTk2NTcxIDM4MC4xOTY1NzEgMCAwIDAtNDIyLjYxOTQyOC01My4zOTQyODZ6IG0yNTUuNDg4LTE2My44NGMwLTIyLjY3NDI4Ni0xOC43MjQ1NzEtNDAuOTYtNDEuODM3NzE0LTQwLjk2SDI4Mi4xMTJhNDEuMzk4ODU3IDQxLjM5ODg1NyAwIDAgMC00MS43NjQ1NzEgNDAuOTZjMCAyMi42NzQyODYgMTguNzI0NTcxIDQwLjk2IDQxLjc2NDU3MSA0MC45Nmg0MTcuOTM4Mjg2YzIzLjExMzE0MyAwIDQxLjgzNzcxNC0xOC4yODU3MTQgNDEuODM3NzE0LTQwLjk2ek02NTguMjg1NzE0IDQ1MC41NmMxNjEuNjQ1NzE0IDAgMjkyLjU3MTQyOSAxMjguMzY1NzE0IDI5Mi41NzE0MjkgMjg2LjcyUzgxOS45MzE0MjkgMTAyNCA2NTguMjg1NzE0IDEwMjRzLTI5Mi41NzE0MjktMTI4LjM2NTcxNC0yOTIuNTcxNDI4LTI4Ni43MiAxMzAuOTI1NzE0LTI4Ni43MiAyOTIuNTcxNDI4LTI4Ni43MnogbS0xMjUuMzY2ODU3IDMyNy42OGg4My42MDIyODZ2ODEuOTJjMCAyMi42NzQyODYgMTguNjUxNDI5IDQwLjk2IDQxLjc2NDU3MSA0MC45NiAyMy4xMTMxNDMgMCA0MS43NjQ1NzEtMTguMjg1NzE0IDQxLjc2NDU3Mi00MC45NnYtODEuOTJoODMuNjAyMjg1YzIzLjExMzE0MyAwIDQxLjgzNzcxNC0xOC4yODU3MTQgNDEuODM3NzE1LTQwLjk2IDAtMjIuNjc0Mjg2LTE4LjcyNDU3MS00MC45Ni00MS44Mzc3MTUtNDAuOTZINzAwLjA1MDI4NlY2MTQuNGMwLTIyLjY3NDI4Ni0xOC42NTE0MjktNDAuOTYtNDEuNzY0NTcyLTQwLjk2YTQxLjM5ODg1NyA0MS4zOTg4NTcgMCAwIDAtNDEuNzY0NTcxIDQwLjk2djgxLjkySDUzMi45MTg4NTdhNDEuMzk4ODU3IDQxLjM5ODg1NyAwIDAgMC00MS44Mzc3MTQgNDAuOTZjMCAyMi42NzQyODYgMTguNzI0NTcxIDQwLjk2IDQxLjgzNzcxNCA0MC45NnoiIGZpbGw9IiNmZmZmZmYiIHAtaWQ9Ijg5MDMiPjwvcGF0aD48L3N2Zz4=)](https://drive.google.com/file/d/1LasG-urCA7rEoITHofBwEk0CloXM0DwX/view?usp=sharing)




Recommended citation: 
```
@misc{wu2024portrait3d,
      title={Portrait3D: Text-Guided High-Quality 3D Portrait Generation Using Pyramid Representation and GANs Prior}, 
      author={Yiqian Wu and Hao Xu and Xiangjun Tang and Xien Chen and Siyu Tang and Zhebin Zhang and Chen Li and Xiaogang Jin},
      year={2024},
      eprint={2404.10394},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
