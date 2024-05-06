---
title: "FusionDeformer: Text-guided Mesh Deformation using Diffusion Models"
collection: publications
permalink: /publication/FusionDeformer
excerpt: '[Hao Xu](https://xh38.github.io/),  **Yiqian Wu**, [Xiangjun Tang](https://yuyujunjun.github.io/), Jing Zhang, Yang Zhang, Zhebin Zhang, Chen Li and [Xiaogang Jin*](http://www.cad.zju.edu.cn/home/jin)'
date: 2024-05-06
venue: "The Visual Computer (Special Issue of CGI'2024)"
paperurl: 'http://www.cad.zju.edu.cn/home/jin/papers/FusionDeformer2024.pdf'
year: '2024'
first_author: 'no'
teaser: 'http://oneThousand1000.github.io/images/publications/FusionDeformer.png'
---
![portrait3d](http://oneThousand1000.github.io/images/publications/FusionDeformer.png)



> **FusionDeformer: Text-guided Mesh Deformation using Diffusion Models**
>
> **[The Visual Computer](http://www.springer.com/computer/computer+imaging/journal/371)** (Special Issue of CGI'2024), Springer, 2024, 39(9-11)
>
> [Hao Xu](https://xh38.github.io/),  Yiqian Wu, [Xiangjun Tang](https://yuyujunjun.github.io/), Jing Zhang, Yang Zhang, Zhebin Zhang, Chen Li and [Xiaogang Jin*](http://www.cad.zju.edu.cn/home/jin)



<b>Abstract:</b>

Mesh deformation has a wide range of applications, including character creation, geometry modeling, deforming animation, and morphing. Recently, mesh deformation methods based on CLIP models demonstrated the ability to perform automatic text-guided mesh deformation. However, using 2D guidance to deform a 3D mesh attempts to solve an ill-posed problem and leads to distortion and unsmoothness, which cannot be eliminated by CLIP-based methods because they focus on semantic-aware features and cannot identify these artifacts. To this end, we propose FusionDeformer, a novel automatic text-guided mesh deformation method that leverages diffusion models. The deformation is achieved by Score Distillation Sampling (SDS), which minimizes the KL-divergence between the distribution of rendered deformed mesh and the text-conditioned distribution. To alleviate the intrinsic ill-posed problem, we incorporate two approaches into our framework. The first approach involves combining multiple orthogonal views into a single image, providing robust deformation while avoiding the need for additional memory. The second approach incorporates a new regularization to address the unsmooth artifacts. Our experimental results show that the proposed method can generate high-quality, smoothly deformed meshes that align precisely with the input text description while preserving the topological relationships. Additionally, our method offers a text2morphing approach to animation design, enabling common users to produce special effects animation. 


[![Paper](https://img.shields.io/badge/Main%20Paper-1?color=58A399&logo=data:image/svg+xml;charset=utf-8;base64,PHN2ZyB0PSIxNzEyNDkwMTQyMjM1IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjU5MTQiIHdpZHRoPSIyMDAiIGhlaWdodD0iMjAwIj48cGF0aCBkPSJNODIzLjI5NiA2MC40MTZxNjUuNTM2IDAgOTkuMzI4IDM4LjR0MzMuNzkyIDkzLjY5NnY1NDMuNzQ0cTAgMjUuNi0yMS41MDQgNDYuMDhsLTE3MS4wMDggMTYzLjg0cS0xMy4zMTIgMTEuMjY0LTIyLjUyOCAxNC4zMzZ0LTIzLjU1MiAzLjA3MkgyNTguMDQ4cS0yMy41NTIgMC00Ny4xMDQtOS43Mjh0LTQxLjk4NC0yNy42NDgtMzAuMjA4LTQzLjAwOC0xMS43NzYtNTUuODA4di02MzQuODhxMC02MC40MTYgMzMuMjgtOTYuMjU2dDk0LjcyLTM1Ljg0aDU2OC4zMnogbS0yMTUuMDQgNjQyLjA0OHExMy4zMTIgMCAyMi41MjgtOS4yMTZUNjQwIDY3MC43MnEwLTE0LjMzNi05LjIxNi0yMy4wNHQtMjIuNTI4LTguNzA0SDI4Ny43NDRxLTEzLjMxMiAwLTIyLjUyOCA4LjcwNFQyNTYgNjcwLjcycTAgMTMuMzEyIDkuMjE2IDIyLjUyOHQyMi41MjggOS4yMTZoMzIwLjUxMnogbTEyOC0xOTIuNTEycTEzLjMxMiAwIDIyLjUyOC05LjIxNlQ3NjggNDc4LjIwOHQtOS4yMTYtMjIuNTI4LTIyLjUyOC05LjIxNkgyODcuNzQ0cS0xMy4zMTIgMC0yMi41MjggOS4yMTZUMjU2IDQ3OC4yMDh0OS4yMTYgMjIuNTI4IDIyLjUyOCA5LjIxNmg0NDguNTEyeiBtNjMuNDg4LTE5MS40ODhxMTMuMzEyIDAgMjIuNTI4LTkuMjE2dDkuMjE2LTIzLjU1MnEwLTEzLjMxMi05LjIxNi0yMi41Mjh0LTIyLjUyOC05LjIxNmgtNTEycS0xMy4zMTIgMC0yMi41MjggOS4yMTZUMjU2IDI4NS42OTZxMCAxNC4zMzYgOS4yMTYgMjMuNTUydDIyLjUyOCA5LjIxNmg1MTJ6IiBwLWlkPSI1OTE1IiBmaWxsPSIjZmZmZmZmIj48L3BhdGg+PC9zdmc+)](http://www.cad.zju.edu.cn/home/jin/papers/FusionDeformer2024.pdf)


Recommended citation: 
```
coming soon.
```
