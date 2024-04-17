---
title: "EyelashNet: A Dataset and A Baseline Method for Eyelash Matting"
collection: publications
permalink: /publication/eyelashnet
excerpt: 'Qinjie Xiao, Hanyuan Zhang, Zhaorui Zhang, **Yiqian Wu**, Luyuan Wang, [Xiaogang Jin](http://www.cad.zju.edu.cn/home/jin/), Xinwei Jiang, [Yongliang Yang](https://www.yongliangyang.net/),  [Tianjia Shao](http://tianjiashao.com/), [Kun Zhou](http://kunzhou.net/).'
date: 2021-12-30
venue: 'ACM Transactions on Graphics (Proceedings of SIGGRAPH Asia 2021)'
paperurl: 'https://dl.acm.org/doi/10.1145/3478513.3480540'
citation: 'http://oneThousand1000.github.io/files/bibtex/EyelashNet.html'
code: 'https://github.com/QinjieXiao/EyelashNet'
video: 'http://www.cad.zju.edu.cn/home/jin/siga2021/demo.mp4'
supplementary_materials: ''
project_page: 'http://www.cad.zju.edu.cn/home/jin/siga2021/siga2021.htm'
year: '2021'
first_author: 'no'
teaser: 'http://oneThousand1000.github.io/images/publications/eyelashnet.jpg'
---

![coarse2fine](http://oneThousand1000.github.io/images/publications/eyelashnet.jpg)



> **EyelashNet: A Dataset and A Baseline Method for Eyelash Matting**
>
> ACM Transactions on Graphics (Proceedings of SIGGRAPH Asia 2021)
>
> Qinjie Xiao, Hanyuan Zhang, Zhaorui Zhang, Yiqian Wu, Luyuan Wang, [Xiaogang Jin*](http://www.cad.zju.edu.cn/home/jin/), Xinwei Jiang, [Yongliang Yang](https://www.yongliangyang.net/), [Tianjia Shao](http://tianjiashao.com/), [Kun Zhou](http://kunzhou.net/)



<b>Abstract:</b>

Eyelashes play a crucial part in the human facial structure and largely affect the facial attractiveness in modern cosmetic design. However, the appearance and structure of eyelashes can easily induce severe artifacts in high-fidelity multi-view 3D face reconstruction. Unfortunately it is highly challenging to remove eyelashes from portrait images using both traditional and learning based matting methods due to the delicate nature of eyelashes and the lack of eyelash matting dataset. To this end, we present EyelashNet, the first eyelash matting dataset which contains 5,400 high-quality eyelash matting data captured from real world and 5,272 virtual eyelash matting data created by rendering avatars. Our work consists of a capture stage and an inference stage to automatically capture and annotate eyelashes instead of tedious manual efforts. The capture is based on a specifically-designed fluorescent labeling system. By coloring the eyelashes with a safe and invisible fluorescent substance, our system takes paired photos with colored and normal eyelashes by turning the equipped ultraviolet (UVA) flashlight on and off. We further correct the alignment between each pair of photos and use a trained matting network to extract the eyelash alpha matte. As there is no prior eyelash dataset, we propose a progressive training strategy that progressively fuses captured eyelash data with virtual eyelash data to learn the latent semantics of real eyelashes. As a result, our method can accurately extract eyelash alpha mattes from fuzzy and self-shadow regions such as pupils, which is almost impossible by manual annotations. To validate the advantage of EyelashNet, we present a baseline method based on deep learning that achieves state-of-the-art eyelash matting performance with RGB portrait images as input. We also demonstrate that our work can largely benefit important real applications including high-fidelity personalized avatar and cosmetic design.

[![Project](https://img.shields.io/badge/EyelashNet-1?label=Project&color=8B93FF&logo=data:image/svg+xml;charset=utf-8;base64,PHN2ZyB0PSIxNzEyNDkwMTA3NzIxIiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjkgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjM4NzUiIHdpZHRoPSIyMDAiIGhlaWdodD0iMjAwIj48cGF0aCBkPSJNMTAwMS40MjMyMzggNDk0LjU5MnEyMS41MDQgMjAuNDggMjIuNTI4IDQ1LjA1NnQtMTYuMzg0IDQwLjk2cS0xOS40NTYgMTcuNDA4LTQ1LjA1NiAxNi4zODR0LTQwLjk2LTE0LjMzNnEtNS4xMi00LjA5Ni0zMS4yMzItMjguNjcydC02Mi40NjQtNTguODgtNzcuODI0LTczLjcyOC03OC4zMzYtNzQuMjQtNjMuNDg4LTYwLjQxNi0zMy43OTItMzEuNzQ0cS0zMi43NjgtMjkuNjk2LTY0LjUxMi0yOC42NzJ0LTYyLjQ2NCAyOC42NzJxLTEwLjI0IDkuMjE2LTM4LjQgMzUuMzI4dC02NS4wMjQgNjAuOTI4LTc3LjgyNCA3Mi43MDQtNzUuNzc2IDcwLjY1Ni01OS45MDQgNTUuODA4LTMwLjIwOCAyNy4xMzZxLTE1LjM2IDEyLjI4OC00MC45NiAxMy4zMTJ0LTQ0LjAzMi0xNS4zNnEtMjAuNDgtMTguNDMyLTE5LjQ1Ni00NC41NDR0MTcuNDA4LTQxLjQ3MnE2LjE0NC02LjE0NCAzNy44ODgtMzUuODR0NzUuNzc2LTcwLjY1NiA5NC43Mi04OC4wNjQgOTQuMjA4LTg4LjA2NCA3NC43NTItNzAuMTQ0IDM2LjM1Mi0zNC4zMDRxMzguOTEyLTM3Ljg4OCA4My45NjgtMzguNHQ3Ni44IDMwLjIwOHE2LjE0NCA1LjEyIDI1LjYgMjQuMDY0dDQ3LjYxNiA0Ni4wOCA2Mi45NzYgNjAuOTI4IDcwLjY1NiA2OC4wOTYgNzAuMTQ0IDY4LjA5NiA2Mi45NzYgNjAuOTI4IDQ4LjEyOCA0Ni41OTJ6TTQ0Ny40MzkyMzggMzQ2LjExMnEyNS42LTIzLjU1MiA2MS40NC0yNS4wODh0NjQuNTEyIDI1LjA4OHEzLjA3MiAzLjA3MiAxOC40MzIgMTcuNDA4bDM4LjkxMiAzNS44NHEyMi41MjggMjEuNTA0IDUwLjY4OCA0OC4xMjh0NTcuODU2IDUzLjI0OHE2OC42MDggNjMuNDg4IDE1My42IDE0Mi4zMzZsMCAxOTQuNTZxMCAyMi41MjgtMTYuODk2IDM5LjkzNnQtNDUuNTY4IDE4LjQzMmwtMTkzLjUzNiAwIDAtMTU4LjcycTAtMzMuNzkyLTMxLjc0NC0zMy43OTJsLTE5NS41ODQgMHEtMTcuNDA4IDAtMjQuMDY0IDEwLjI0dC02LjY1NiAyMy41NTJxMCA2LjE0NC0wLjUxMiAzMS4yMzJ0LTAuNTEyIDUzLjc2bDAgNzMuNzI4LTE4Ny4zOTIgMHEtMjkuNjk2IDAtNDcuMTA0LTEzLjMxMnQtMTcuNDA4LTM3Ljg4OGwwLTIwMy43NzZxODMuOTY4LTc2LjggMTUyLjU3Ni0xMzkuMjY0IDI4LjY3Mi0yNi42MjQgNTcuMzQ0LTUyLjczNnQ1Mi4yMjQtNDcuNjE2IDM5LjQyNC0zNi4zNTIgMTkuOTY4LTE4Ljk0NHoiIHAtaWQ9IjM4NzYiIGZpbGw9IiNmZmZmZmYiPjwvcGF0aD48L3N2Zz4=)](http://www.cad.zju.edu.cn/home/jin/siga2021/siga2021.htm)
[![Paper](https://img.shields.io/badge/Main%20Paper-1?color=58A399&logo=data:image/svg+xml;charset=utf-8;base64,PHN2ZyB0PSIxNzEyNDkwMTQyMjM1IiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjU5MTQiIHdpZHRoPSIyMDAiIGhlaWdodD0iMjAwIj48cGF0aCBkPSJNODIzLjI5NiA2MC40MTZxNjUuNTM2IDAgOTkuMzI4IDM4LjR0MzMuNzkyIDkzLjY5NnY1NDMuNzQ0cTAgMjUuNi0yMS41MDQgNDYuMDhsLTE3MS4wMDggMTYzLjg0cS0xMy4zMTIgMTEuMjY0LTIyLjUyOCAxNC4zMzZ0LTIzLjU1MiAzLjA3MkgyNTguMDQ4cS0yMy41NTIgMC00Ny4xMDQtOS43Mjh0LTQxLjk4NC0yNy42NDgtMzAuMjA4LTQzLjAwOC0xMS43NzYtNTUuODA4di02MzQuODhxMC02MC40MTYgMzMuMjgtOTYuMjU2dDk0LjcyLTM1Ljg0aDU2OC4zMnogbS0yMTUuMDQgNjQyLjA0OHExMy4zMTIgMCAyMi41MjgtOS4yMTZUNjQwIDY3MC43MnEwLTE0LjMzNi05LjIxNi0yMy4wNHQtMjIuNTI4LTguNzA0SDI4Ny43NDRxLTEzLjMxMiAwLTIyLjUyOCA4LjcwNFQyNTYgNjcwLjcycTAgMTMuMzEyIDkuMjE2IDIyLjUyOHQyMi41MjggOS4yMTZoMzIwLjUxMnogbTEyOC0xOTIuNTEycTEzLjMxMiAwIDIyLjUyOC05LjIxNlQ3NjggNDc4LjIwOHQtOS4yMTYtMjIuNTI4LTIyLjUyOC05LjIxNkgyODcuNzQ0cS0xMy4zMTIgMC0yMi41MjggOS4yMTZUMjU2IDQ3OC4yMDh0OS4yMTYgMjIuNTI4IDIyLjUyOCA5LjIxNmg0NDguNTEyeiBtNjMuNDg4LTE5MS40ODhxMTMuMzEyIDAgMjIuNTI4LTkuMjE2dDkuMjE2LTIzLjU1MnEwLTEzLjMxMi05LjIxNi0yMi41Mjh0LTIyLjUyOC05LjIxNmgtNTEycS0xMy4zMTIgMC0yMi41MjggOS4yMTZUMjU2IDI4NS42OTZxMCAxNC4zMzYgOS4yMTYgMjMuNTUydDIyLjUyOCA5LjIxNmg1MTJ6IiBwLWlkPSI1OTE1IiBmaWxsPSIjZmZmZmZmIj48L3BhdGg+PC9zdmc+)](https://dl.acm.org/doi/10.1145/3478513.3480540)
[![Video](https://img.shields.io/badge/Video-1?color=FDA403&logo=data:image/svg+xml;charset=utf-8;base64,PHN2ZyB0PSIxNzEyNDkwMjU5OTgxIiBjbGFzcz0iaWNvbiIgdmlld0JveD0iMCAwIDEwMjQgMTAyNCIgdmVyc2lvbj0iMS4xIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHAtaWQ9IjEyOTE2IiBpZD0ibXhfbl8xNzEyNDkwMjU5OTgyIiB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCI+PHBhdGggZD0iTTYyMy4zMzAyOTE0ODQ0NDQ0IDIwMy44OTk4OTE0ODQ0NDQ0Mkg5Ny43NDc3NTI5NjAwMDAwMXMtODguMDI4NjAyNTk1NTU1NTUgMC04OC4wMjg2MDI1OTU1NTU1NSA4NS40Mzk1MjU1NDY2NjY2NnY0MzIuMzc1NzgyOTY4ODg4ODdjMCA4NS40Mzk1MjU1NDY2NjY2NiA4OC4wMjg2MDI1OTU1NTU1NSA4NS40Mzk1MjU1NDY2NjY2NiA4OC4wMjg2MDI1OTU1NTU1NSA4NS40Mzk1MjU1NDY2NjY2Nmg1MjUuNTgyNTM4NTI0NDQ0NHM4OC4wMjg2MDI1OTU1NTU1NSAwIDg4LjAyODYwMjU5NTU1NTU1LTg1LjQzOTUyNTU0NjY2NjY2VjI5MS45Mjg0OTQwODAwMDAwNmMwLTg4LjAyODYwMjU5NTU1NTU1LTg4LjAyODYwMjU5NTU1NTU1LTg4LjAyODYwMjU5NTU1NTU1LTg4LjAyODYwMjU5NTU1NTU1LTg4LjAyODYwMjU5NTU1NTU1ek05ODMuMjExOTMwNzM3Nzc3OCAyNDcuOTE0MTkyMjEzMzMzM2MtNy43NjcyMzAwMDg4ODg4ODgtMi41ODkwNzcwNDg4ODg4ODg2LTE1LjUzNDQ1ODg3OTk5OTk5OS0yLjU4OTA3NzA0ODg4ODg4ODYtMjAuNzEyNjExODQgMi41ODkwNzcwNDg4ODg4ODg2bC0xNzMuNDY4MTI5MjggMTM0LjYzMTk4MDM3MzMzMzMzYy01LjE3ODE1Mjk2IDUuMTc4MTUyOTYtNy43NjcyMzAwMDg4ODg4ODggMTAuMzU2MzA1OTItNy43NjcyMjg4NzExMTExMTE1IDE1LjUzNDQ1ODg3OTk5OTk5OXYyMTQuODkzMzUyOTYwMDAwMDJjMCA1LjE3ODE1Mjk2IDIuNTg5MDc3MDQ4ODg4ODg4NiAxMi45NDUzODI5Njg4ODg4ODggNy43NjcyMjg4NzExMTExMTE1IDE1LjUzNDQ2MDAxNzc3Nzc3N2wxNzMuNDY4MTI5MjggMTM0LjYzMTk3OTIzNTU1NTU4YzIuNTg5MDc3MDQ4ODg4ODg4NiAyLjU4OTA3NzA0ODg4ODg4ODYgNy43NjcyMzAwMDg4ODg4ODggNS4xNzgxNTI5NiAxMi45NDUzODE4MzExMTExMTIgNS4xNzgxNTQwOTc3Nzc3NzcgMi41ODkwNzcwNDg4ODg4ODg2IDAgNS4xNzgxNTI5NiAwIDEwLjM1NjMwNzA1Nzc3Nzc3OC0yLjU4OTA3NzA0ODg4ODg4ODYgNy43NjcyMzAwMDg4ODg4ODgtMi41ODkwNzcwNDg4ODg4ODg2IDEwLjM1NjMwNTkyLTEwLjM1NjMwNTkyIDEwLjM1NjMwNTkyLTE4LjEyMzUzNTkyODg4ODg4OFYyNjYuMDM3NzI4MTQyMjIyMjVjMC03Ljc2NzIzMDAwODg4ODg4OC01LjE3ODE1Mjk2LTE1LjUzNDQ1ODg3OTk5OTk5OS0xMi45NDUzODI5Njg4ODg4ODgtMTguMTIzNTM1OTI4ODg4ODg4eiIgZmlsbD0iI2ZmZmZmZiIgcC1pZD0iMTI5MTciPjwvcGF0aD48L3N2Zz4=)](http://www.cad.zju.edu.cn/home/jin/siga2021/demo.mp4)
[![Github](https://img.shields.io/github/stars/QinjieXiao/EyelashNet)](https://github.com/QinjieXiao/EyelashNet)

Recommended citation: 
```
@article{10.1145/3478513.3480540,
author = {Xiao, Qinjie and Zhang, Hanyuan and Zhang, Zhaorui and Wu, Yiqian and Wang, Luyuan and Jin, Xiaogang and Jiang, Xinwei and Yang, Yong-Liang and Shao, Tianjia and Zhou, Kun},
title = {EyelashNet: a dataset and a baseline method for eyelash matting},
year = {2021},
publisher = {Association for Computing Machinery},
volume = {40},
number = {6},
issn = {0730-0301},
journal = {ACM Trans. Graph.},
articleno = {217},
}
```
